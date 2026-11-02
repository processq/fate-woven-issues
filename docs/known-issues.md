---
title: Known issues
nav_order: 7
description: "What is not finished in Fate Woven: rough edges, mod notes and first-pass balance."
image: /assets/banner-known-issues.jpg
---

![Known issues](assets/banner-known-issues.jpg)

# Known issues
{: .visually-hidden}

Fate Woven is in beta and changes fast, so here is what we know is not finished. If you hit any of these, or something not listed, please tell us on the [issues page](https://github.com/processq/fate-woven-issues/issues/new/choose) or on Discord. Set General > Logging to Detailed first and attach `BepInEx/LogOutput.log`.

## Rough edges
- **Everyone in a game must run the exact same Fate Woven version.** A different version can't join, so update together.
- **PvP (new, off by default).** A server host can turn on the "Fate Woven PvP" setting. In Valheim, your PvP switch turns off after you die until you open your inventory, even though its icon still shows on. With the setting off, Fate Woven treats other players as friends and only plain weapon damage works between them.

## Mods
- **Creature Level and Loot Control 4.6.4** from Thunderstore crashes with this game version. Use version 5.x from Hexium.
- **Epic Loot** works even though it shows a "not compatible" warning.

## First-pass balance
- **XP and mastery are sped up for the beta,** so you can reach more of the game quickly. Expect levelling and mastery to be slower after the beta.
- All balance is tuned against normal enemies, not yet against levelled-up enemies from enemy mods such as Creature Level and Loot Control or Monstrum. Expect it to change.
- First numbers, likely to change: the new set pieces, the Epic second copies, Ward-Breaker Blow's rebuilt shield, the Warding Rune beam's stacking shields, Last Command's shield of 30, Reaper's Toll's 6 refunds a minute, and control on big enemies (half length, then 6 seconds of immunity).
- Effects that fire "about N times a minute" on rare events now fire as often as their cards say, so they are stronger than before.

---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
