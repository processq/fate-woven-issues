---
title: For mod authors
nav_order: 4
parent: Servers and mods
description: "Extend Fate Woven: content packs in JSON, and the code API for other Valheim mods."
image: /assets/banner-for-mod-authors.jpg
---

![For mod authors](assets/banner-for-mod-authors.jpg)

# For mod authors
{: .visually-hidden}

Two ways to extend Fate Woven, both soft: it plays the same without any add-on, and a broken add-on is logged and switched off, never crashing the rest. Everyone in a game needs the same packs.

The API's class is `FateWoven.FateWovenAPI`. The old `ValheimWildcard.WildcardAPI` still works but is obsolete, so use the new name.

## 1. Content packs (data only, no code)

Put JSON files in `BepInEx/config/FateWoven/packs/<pack name>/<table>.json`. Each file is a JSON array in the same format as the mod's `data/<table>.json` (`base_abilities`, `modifier_runes`, `element_riders`, ...).

- **New card:** a name the table doesn't have. It's tagged with your pack, and its tooltip ends with "(pack name)".
- **Change one of ours:** same name plus `"override": true`. Your fields replace ours.
- **Templates (the way to add something that plays):**
  - A base ability with `"template": "Rune Bolt"` plays with Rune Bolt's code, under your name, text, element, tags and numbers. Fields you leave out come from the template.
  - A modifier rune with `"template": "Wide"` runs Wide's code at your card's `"strength"` (1.0 if none).
- `"enabled": false` skips a card. A pack folder whose name starts with `_` is off.
- **Server switch (0.2.850):** the server's `Release → CardsOff` setting (synced to every player) lists pack folder names or card names, comma-separated. A named pack's new cards, or a named card, aren't offered in drafts, and owned ones stop working until it's removed from the list. A pack's changes to existing cards stay; use the `_` prefix to undo those.
- Packs are part of the card-data check, so every player in a game needs the same packs.

Example, `packs/frostpack/base_abilities.json`:

```json
[{ "name": "Ice Lance", "template": "Rune Bolt", "default_element": "Frost", "rarity": "Common", "cost": 12,
   "tooltip": "A lance of ice." }]
```

## 2. Code API (`FateWoven.FateWovenAPI`; the old `ValheimWildcard.WildcardAPI` still works but is obsolete)

Add `[BepInDependency("FateWoven", BepInDependency.DependencyFlags.SoftDependency)]` and call the static class by reference or reflection. Only primitives, vanilla types and JSON cross the boundary.

- `ApiVersion` (1) and `HasEndpoint(name)`: check before using a newer part.
- **Queries:**
  - `GetPlayerJson()`: level, the bar (ability, element, runes, mastery) and the power level.
  - `IsWildcardHit(HitData)`
  - `GetPowerLevel()`
- **Rewards:** `GrantXp(amount, why)` and `GrantRune(cardName)`.
- **Events** (the local player's):
  - `AbilityCast(ability, element)`
  - `HitLanded(target, amount, element)`
  - `StatusApplied(target, key)`
  - `Killed(victim)`
- **Registration:**
  - `RegisterRuleHandler(name, (caster, target, ruleJson) => bool)`: a card rule `{"handler": name}` runs your code inside Fate Woven's rule flow.
  - `RegisterUndeadProvider(character => bool)`: your creatures count as undead for Holy.
  - `RegisterWeaponElementProvider(item => "Fire" | null)`: your weapons apply their element's status every third hit.
  - `RegisterElementStatus(element, statusKeys...)` (0.2.1574): the status (or statuses) your element's hits apply, by Fate Woven status key ("Chilled", "Venom", "Marked", "Burning", "Stagger" and so on). False for our twelve elements, which keep theirs, or an unknown key.
  - `RegisterDamageType("void", target => 1.5f)` (0.2.851): a new damage type. It lands as untyped damage (no stagger, like Holy and Shadow) times your multiplier for the target (1 normal, 2 weak, 0.5 resisted, 0 immune), and the number shows yellow when weak and grey when resisted. Built-in names (slash … shadow) are refused.
  - `MapElementToDamageType("Void", "void")` (0.2.851): your element deals that type. Our twelve elements keep their own. Data-only alternative: `"damageType": "void"` on the pack's element_runes card (no multiplier registered = x1 to everything). `"damage_type"` stays the player-facing sentence.

A listener or handler that throws is logged with its assembly's name. Handlers and providers that throw are switched off.

---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
