# Statuses

[Home](index.md) | [Getting started](getting-started.md) | [Abilities](abilities.md) | [Runes](runes.md) | [Elements](elements.md) | [Statuses](statuses.md) | [Gods](gods.md) | [Sets](sets.md) | [Utility and pets](utility-and-pets.md) | [Interface and multiplayer](interface-and-multiplayer.md) | [Report a bug](https://github.com/processq/fate-woven-issues/issues/new/choose)

## Buff

### Charged (Lightning)

Your next hit applies Shocked to its target, consuming Charged. Re-applying refreshes it. Cards may set their own duration or a stronger version; that only changes that application. Lasts 6s.

### Enraged (Steel)

+10% damage. Doesn't stack: the strongest version applies. Cards may set their own duration or a stronger version; that only changes that application. Lasts 8s.

### Inspired (Steel (Skald) / Holy)

+15% damage and +20% stamina regen. Doesn't stack: the strongest version applies. Cards may set their own duration or add their own extras, stated as separate effects; they don't change what Inspired means. Lasts 8s.

### Stealthed (Shadow)

Unseen until you attack. Enemies that lose track of you become unaware again, so your next hit on each is a sneak attack: weapon swings and weapon abilities use the weapon's bonus (x3, knives x6), Shadow abilities x6, other abilities x2. Vanilla's 5-minute sneak immunity per enemy applies; raid spawns are never unaware. Fate Woven's own '+X% from Stealthed or behind' bonuses don't multiply with a sneak attack: the bigger applies. Lasts Varies.

## CC

### Feared (Shadow / any)

Flees from the source and cannot attack. Bosses ignore Fear. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says (usually 2-3s).

### Rooted (Nature / Earth / Water)

Cannot move but can still attack. Bosses are slowed 40% instead. Then immune for 6s. Cards may set their own duration or a stronger version; that only changes that application. Lasts 1.5s.

### Taunted (Any)

Must attack the taunter. Bosses are taunted for half as long. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says.

## Debuff

### Blinded (Any)

Its attacks miss 40% of the time. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says.

### Cursed (None)

Deals 12% less damage, and healing it would receive damages it instead. One Curse per target; re-applying refreshes it. Applied only by the cards that name it (blessings, signatures, the rune set); Shadow hits don't Curse. Cards may set their own duration or add their own extras, stated as separate effects; they don't change what Cursed means. Lasts 8s.

### Exposed (Any)

The target's resistance to one element is broken: from an Epic rune it moves 50% of the way back to normal, from a Legendary rune all the way, and Immune becomes Resistant (bosses: Very resistant). Weaknesses don't change. Never stacks: one Exposed per damage type, the biggest applies, and slot strength or copies don't raise it. Levels come from the card: Sworn and Epic synergies 50%, Breaking Call 40%, Shatterguard 50%, Fracture Shot 60%, Legendaries and Unmaking 100%. It helps every player's hits. Shown as a cracked ring in the element's colour. Lasts 5s (Epic), 6s (Legendary).

### Hobbled (Any (melee))

Crippled: can't dodge, sprint or flee, moves 50% slower and takes 25% more Stagger. Casting takes 25% longer (cast time only, never cost; see Slowed casting). Bosses are only Slowed 25%. Cards may set their own duration or a stronger version; that only changes that application. Lasts 4s.

### Marked (Holy)

Visible to you and your allies through walls. It takes 10% more damage from Fate Woven ability hits (there are no crits), and allies hitting it heal 2% of the damage dealt. Cards may set their own duration or a stronger version; that only changes that application. Lasts 8s.

### Mud (Earth + Water)

Mired: 40% slower and takes 25% more stagger. Cards may set their own duration or a stronger version; that only changes that application. Lasts 4s.

### Shocked (Lightning)

The next hit on the target deals +20% damage and arcs 50% of it to 1 enemy within 6m, consuming Shocked. Wet targets take x1.5 Lightning damage. Cards may set their own duration or a stronger version; that only changes that application. Lasts 6s.

### Silenced (Any)

Cannot use special attacks or spells (for enemies: its ranged and magic attacks). Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says.

### Slowed (Any)

Moves slower by the amount the card says. Several slows don't add up; the strongest applies. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says.

### Spellbound (Arcane)

The next status another element applies to the target lasts +50% and lands 25% stronger (stacks, seconds or strength, whichever it has), then Spellbound is used up. It helps every player's statuses. Applied by the Arcane riders, Runelight and the Arcane signatures; plain Arcane hits don't apply it. Lasts 8s.

### Sundered (Steel)

Physical resistances broken: the target's Blunt, Slash and Pierce resistances each move 15% of the way back to normal (Resistant x0.5 becomes x0.575), for every player's hits; weaknesses don't change. Applied by every Steel hit and by cards that name it; cards may set a stronger version. Lasts 6s.

### Wet (Water (native Valheim))

Valheim's own Wet, left exactly as vanilla: slower stamina regen and sooner Cold, but it also reduces fire damage taken. Wet enemies take x1.5 Lightning and Frost damage (vanilla's own Weak; Fate Woven adds nothing on top) and Frost hits add 1 extra Chilled stack; Fire on a Wet target shortens Burning and consumes Wet. Yagluth follows vanilla: Fate Woven's Water can't soak him. Lasts 12s from Water hits (overrides vanilla's longer Wet from these hits; rain and swimming keep vanilla's own).

## DoT

### Bleeding (Blood / Steel)

40% of the hit that applied it, dealt over 6s, doubled while the target moves. Re-applying refreshes it with the new hit and adds 10% each time, up to 80% of the hit. Never a share of max health. Steel's Bleeding is lighter: 20% of the hit over 4s. One shared pool per target for the whole group, up to the 80% cap. A source that deals no damage (a pure control, a parry, a struck decoy) counts its hit as 49 x TierScale, a Rune Bolt's hit. Cards may set their own duration or a stronger version; that only changes that application. Lasts 6s (Steel's lighter Bleeding: 4s).

### Burning (Fire)

30% of the hit as Fire damage over 5s. Re-applying refreshes it and adds 10% (max 60%). Wet targets burn half as long and lose Wet instead. One shared pool per target for the whole group, up to the 60% cap. On Fire-immune creatures it still lands with 0 damage, so payoffs that read Burning still work. Cards may set their own duration or a stronger version; that only changes that application. Lasts 5s.

## Hard CC

### Asleep (Any (control))

Cannot act until damaged or the duration ends. Any damage wakes it. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says.

### Confused (Any (control))

Attacks the nearest other enemy instead of the player. Bosses can't be Confused. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says, at most 4s from abilities and runes. A blessing's own active can name a longer time (Taunts at the Sea Giant's Feast: 8s, on a 240s cooldown). Control ranks and the immunity afterwards still apply..

### Frozen (Frost)

Cannot act. Breaks early on a heavy hit after 1s. Bosses are slowed 50% instead. Then immune to Frozen for 8s. Payoff target for Shatter effects. Cards may set their own duration or a stronger version; that only changes that application. Lasts 2s.

### Petrified (Earth)

Staggered twice within 6s by Earth hits: turned to stone: cannot act and takes +30% Blunt damage. Bosses and stagger-immune creatures are Slowed 50% for its length instead. Then immune for 10s. Cards may set their own duration or a stronger version; that only changes that application. Stagger-immune creatures can't reach it through Earth's double stagger. Lasts 2s.

### Smothered (Any (Smother))

A bubble of the element covers the head: cannot move, attack or cast. Takes a little damage each second, rising 15% a second. The bubble has a shell that hits can break, which ends the effect. Creatures that don't breathe (undead, spirits, golems, Surtlings) are Blinded instead. Large and Boss creatures follow the control meter. Then immune to Smothered for 8s. Cards may set their own duration or a stronger version; that only changes that application. Lasts 3s.

### Staggered (Earth / Steel (native Valheim))

Valheim's own stagger: the target is open to bonus damage, as after a parry. Earth: Staggered twice within 6s by Earth hits becomes Petrified. Stagger-immune creatures (bosses, Gjall, Drakes, Deathsquitos, Blobs and Oozers, Growths, Leeches, Serpents, Deer and other small or flying creatures) can't be Staggered by building it up; cards that pay off on Staggered do nothing to them. A card that Staggers outright Slows them 50% for 2s instead. Lasts ~2s.

### Stunned (Any)

Cannot move, attack or cast. Bosses and stagger-immune creatures are Slowed 50% for the stun's length instead. Cards may set their own duration or a stronger version; that only changes that application. Lasts As the card says (usually 1-2s).

## Stacking DoT (max 10)

### Venom (Poison)

Each stack deals 2.5% of the hit that added it as Poison damage per second and reduces healing received by 3%. At 10 stacks the target also deals 10% less damage. One shared pool per target for the whole group, up to the 10-stack cap. On Poison-immune creatures the stacks still land with 0 damage, so the healing cut, the 10-stack damage cut and the payoffs that read Venom still work. Cards may set their own duration or a stronger version; that only changes that application. Lasts 8s per stack: each stack runs out on its own.

## Stacking debuff (max 5)

### Chilled (Frost)

+8% cast time per stack (cast time only, never cost; at most +50% from statuses together, see Slowed casting). No movement or attack slow of its own: Frost hits start vanilla's Frost slow, which stays Frost's movement slow, and Chilled builds on it toward Frozen. At 5 stacks the target becomes Frozen (some cards Freeze at fewer stacks; they say so). Cards may set their own duration or a stronger version; that only changes that application. Lasts 6s, refreshed per stack.


---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
