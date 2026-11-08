---
title: Settings
nav_order: 1
parent: Servers and mods
description: "Every Fate Woven setting that matters for players and server hosts: power level, quests, Re-weave, content switches and logging."
image: /assets/banner-settings.jpg
---

![Settings](assets/banner-settings.jpg)

# Settings
{: .visually-hidden}

Fate Woven's settings live in `BepInEx/config/FateWoven.cfg`, and the Abilities panel has a **Settings** button for the ones you change most. Most settings are **server settings**: on a server, only the host's file matters, and everyone who joins uses the host's values. The last section lists the settings that are yours alone.

## Server settings

### Balance
| Setting | Default | What it does |
|---|---|---|
| Balance > PowerLevel | Auto | How strong abilities are, to match your enemies (damage, heals and shields; costs, cooldowns and controls don't change). **Auto** picks from the enemy mods installed. **Vanilla**: plain Valheim enemies. **Modded**: Creature Level and Loot Control, Star Level System, Monstrum or Path of Valheiman at their usual settings. **HardModded**: high star levels or stacked enemy mods. **Custom**: use PowerScale. |
| Balance > PowerScale | 1.0 | Custom's multiplier on ability damage, heals and shields, from 0.5 to 2.0. Used only when PowerLevel is Custom. |
| Balance > ShieldCapOfHealth | 0.5 | Shields stack, but nobody holds more than this share of their max health (0.5 to 2). |
| Balance > DamageBonusCap | 0 | Caps the total ability damage bonus at 1 plus this value (2 = at most +200%). 0 means no cap. |

### Levels and eitr
| Setting | Default | What it does |
|---|---|---|
| Progression > UnlockLevels | 1,5,12,20,28,36,45,53 | The level at which each biome's cards open for drafts. |
| Eitr > EitrPoolBase and EitrPoolPerLevel | 30 and 2 | Your Fate Woven eitr at level 1, and how much it grows each level. |
| Eitr > PoolRegenOutOfCombat and PoolRegenInCombat | 2.0 and 1.5 | Eitr regained a second out of and in combat. |

Two server settings change the pace: Progression > Levelling speed and Mastery > Mastery speed (both 1.0 by default, from 0.25 to 4). 2.0 means twice as fast, 0.5 half as fast. They are server rules, so one player cannot set them for the others. Existing characters keep their level and mastery.

### Quests
| Setting | Default | What it does |
|---|---|---|
| Quests > QuestsEnabled | true | Off: the quest board can't be built and no new quest can be taken. |
| Quests > NoticesPerBoard | 3 | Notices each character has on the plain board (1 to 12). Each board rank adds more, up to 6 on top. |
| Quests > NoticeExpireDays | 3 | In-game days before a notice nobody took is replaced. |
| Quests > ActiveMax | 3 | Active quests a character can hold (1 to 6). |
| Quests > ShareBonus | 0.75 | A group quest's counts grow by this much for each extra member (0 to 2). |
| Party > PartyEnabled | on | Turns the [party](party.md) system on or off. |
| Party > PartySize | 6 | The most players in one party (2 to 10). |
| Party > PartyXpRange | 60 | Metres: members this close to a kill get its XP even if they did not hit it, and Fellowship counts members this close to each other. |
| Party > FellowshipXpPct | 5 | The extra kill XP, in percent, while another member is in range. 0 turns it off. |
| Party > PartyFriendlyFire | off | On: members' plain weapon hits can hurt each other as Valheim's PvP allows. Off: they cannot. Fate Woven abilities never hurt party members either way. |
| Quests > TokenSoftCap | true | Each reroll, banish or lock earned lately halves the chance of another one, so they cannot be farmed. |

### Content switches
Everything is on by default. Set one to false to leave that part out of the game for everyone.

| Setting | What it switches |
|---|---|
| Release > Blessings | Blessings and duo blessings (favour, altars, offers). |
| Release > SignatureAbilities | Signature abilities. |
| Release > AdvancedRunes | Synergy, meta, set, Sworn and trophy runes. |
| Release > EpicLegendaryRunes and LegendaryRunes | Epic runes and slot, and Legendary runes and slot. |
| Release > the utility switch | Utility abilities and the two utility slots. Its key keeps an old name from an earlier version; it is the one in the Release section that mentions utility. |
| Release > CardsOff | Content packs or cards to switch off, separated by commas. A pack's folder name switches off its new cards; a card's name switches off that card. |

### PvP
| Setting | Default | What it does |
|---|---|---|
| Fate Woven PvP | off | When on, players who both have Valheim's PvP switch on can hurt each other with Fate Woven abilities. Hard control lasts half as long on players and is followed by a short immunity, killing a player gives no XP or kill effects, and a PvP death skips the death penalty but still ends a Hel's Road run. Off: co-op, Fate Woven abilities never hurt players. |
| PvP damage % | 40 | How much of Fate Woven's ability damage reaches another player (and their pets) in PvP. Plain weapon swings stay as in Valheim; only Fate Woven's added bonus is cut. |

### Re-weave and Hel's Road
| Setting | Default | What it does |
|---|---|---|
| Release > ReWeave | true | Players at level 60 can Re-weave. |
| Release > Allow Redo my picks | true | Lets characters made before the new draft schedule redo their picks once. Off: the button is gone. |
| Release > ReWeaveUndo | auto | auto, on or off: whether a player can undo their last Re-weave until level 5 of the new run. Auto is on in the beta and off in the full release. |
| Release > HelsRoadDeaths | Easy | Easy: only a kill by a creature, boss or player ends a Hel's Road run. Hardcore: any death does, including falls and drowning. |

## Server rules window
You do not have to edit the file. Open Settings from the Abilities panel and choose the **Server rules** tab. It lists every server rule (79 of them) with its value and a short description.

- **The host edits.** In single player, or when you host, you can change a rule and it saves at once and reaches every player.
- **Everyone else reads.** On someone else's server, the window shows the host's values and you cannot change them.
- **Reload needed.** A few rules are marked (reload required). They take effect after a restart, and when you close the window a notice names the rules you changed that need one.
- Your own settings also show in SeneaL UI's settings window when it is installed.

## Your own settings
These affect only your PC.

| Setting | Default | What it does |
|---|---|---|
| General > Logging | Normal | Quiet: errors only. Normal: the usual output. **Detailed**: adds a line for every ability hit, rider and blessing effect. Set it to Detailed before you report a bug and attach `BepInEx/LogOutput.log`. The same warning is written at most 5 times, then a "(repeated N times)" line. |
| Visuals > EffectsLevel | Full | Full, Reduced or Minimal. Lower it if the game stutters during big fights. |
| UI > ShowHints | false | The raven brings short tips the first time you meet each system. |
| UI > XpShows | none | What the XP line under the bar shows: none, numbers or percent. Click the line (inventory open) to change it. |
| Visuals > CompendiumEntries | true | Fate Woven's entries in the compendium. |
| UI > PetHealthShows | numbers | What the pet window's health bar shows: numbers, percent or none. |

**Every key can be changed** in the Keys section, and there are three ways to cast. The most popular: configurable hotkeys for each bar slot. Set each one to any key you like, such as the numpad, and one press casts that ability. Or ready an ability with the on-screen wheel (hold B and flick toward it), or step with [ and ], then press Cast. See [Companion mods](companion-mods.md) for keys that clash with other mods.


---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
