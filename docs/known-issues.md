---
title: Known issues
nav_order: 8
description: "What is not finished in Fate Woven: rough edges, mod notes and first-pass balance."
image: /assets/banner-known-issues.jpg
---

![Known issues](assets/banner-known-issues.jpg)

# Known issues
{: .visually-hidden}

Fate Woven is in beta and changes fast, so here is what we know is not finished. If you hit any of these, or something not listed, please tell us on the [issues page](https://github.com/processq/fate-woven-issues/issues/new/choose) or on Discord. Set General > Logging to Detailed first and attach `BepInEx/LogOutput.log`.

## Rough edges
- **Everyone in a game must run the exact same Fate Woven version.** A different version can't join, so update together.
- **Parties, group quests and trading are new and have been tested on two PCs only,** so expect rough spots with more real players in a party. Please report what you see.
- **Legendary quests (the altar hunts) appear only with Creature Level and Loot Control 5.x installed,** and are new: tell us if a hunt doesn't start, can't be finished or pays the wrong reward.
- **A character last played with a newer Fate Woven can't be played with an older one.** The game says so and keeps the save as it was, so update the mod to play it.
- **PvP (new, off by default).** A server host can turn on the "Fate Woven PvP" setting. In Valheim, your PvP switch turns off after you die until you open your inventory, even though its icon still shows on. With the setting off, Fate Woven treats other players as friends and only plain weapon damage works between them.
- **Turning Hue against another player (PvP) is not checked yet.** Its lent status is meant to land at 60% there too, but nobody has seen it work in play.

## Mods
- **Creature Level and Loot Control 4.6.4** from Thunderstore crashes with this game version. Use version 5.x from Hexium.
- **Epic Loot** works even though it shows a "not compatible" warning.
- **JatifyUI** works with Fate Woven as one panel in Jatify's spot. If a Fate Woven window still overlaps one of Jatify's, tell us which.
- **Path of Valheiman** works with Fate Woven, but the two together are not balanced and will feel very strong. Its level is the one level, and Re-weave and Hel's Road are not available with it. Balance may follow player feedback.

## First-pass balance
- **Levelling and mastery were re-tuned.** Early levels are quick and late levels take much longer. Existing characters keep their level and mastery, and two server sliders (Levelling speed and Mastery speed) change the pace.
- All balance is tuned against normal enemies, not yet against levelled-up enemies from enemy mods such as Creature Level and Loot Control or Monstrum. Expect it to change.
- First numbers, likely to change: the new set pieces, the Epic second copies, Ward-Breaker Blow's rebuilt shield, the Warding Rune beam's stacking shields, Last Command's shield of 30 and Reaper's Toll's 6 refunds a minute.
- The 0.2.1786 balance pass put every rune on one scale (Epic and Legendary were pulled toward the middle, Common to Rare were cut, control and slot unlocks were lowered). It is a first baseline: expect numbers to move with player feedback.
- Effects that fire "about N times a minute" on rare events now fire as often as their cards say, so they are stronger than before.
- **Mastery now comes from real use** (damage done, controls landed, healing, shielding, time in a fight for stances, buffs and pets). The rates are first numbers: tell us if an ability ranks up much faster or slower than the others. The new Split (2 copies at 60%) and the out-levelling XP fade are first numbers too.

---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
