---
title: What's new
nav_order: 9
description: "Every Fate Woven beta release, newest first."
image: /assets/banner-whats-new.jpg
---

![What's new](assets/banner-whats-new.jpg)

# What's new
{: .visually-hidden}

Fate Woven is in beta, and every release is listed here, newest first. Please report bugs, issues and requests on the [issues page](https://github.com/processq/fate-woven-issues/issues/new/choose).


## 0.2.1801 (beta)
- This hotfix is a systems rework: runes now come from your drafts, quests and boss kills.
- Rune stones no longer drop, and Rune Finder I and II are gone.
- Epic Loot support is now quest rewards only.
- Re-weave keeps every set piece, set element rune and boss trophy rune.
- Rune stones no longer drop. Set pieces still come from their current sources for now.
- Rune Finder I and II are removed.
- Bounty-Sworn is removed. If you owned it, you get a free rune draft for each copy.
- The two unused socket settings are removed.
- Epic Loot support is quest rewards only: no gear effects and no bounty XP.
- Epic Loot and Therzie weapons no longer apply element statuses.
- Re-weave keeps every set piece, set element rune and boss trophy rune. A boss's trophy is not offered again.
- Holy and Shadow runes describe their damage type correctly.
- Nature no longer lists a 1% max HP regen line, and Water no longer lists a steam burst (neither was in the game).
- Hel's Harvest now says it works on non-boss enemies.

## 0.2.1800 (beta)
- Hotfix, only needed if you use SeneaL UI. Everyone else can stay on 0.2.1786.
- With SeneaL UI, the Abilities and Mastery tabs open their panels, and the panels use SeneaL UI's look.
- With SeneaL UI, the buff column shows again.
- With SeneaL UI, the ability bar and the pet window use SeneaL's slots, buttons and fonts.
- The Abilities and Mastery tabs now open their panels, which were hidden, and the panels use SeneaL UI's look.
- The empty spot beside SeneaL's tabs no longer opens a panel.
- The buff column now shows (SeneaL had hidden it along with the food icons).
- The shield column is narrower.
- The ability bar and the pet window use SeneaL UI's slots, buttons and fonts; the pet health bar stays red.

## 0.2.1786 (beta)
- 2,086 ability and rune combinations now work, 275 more than before, across 135 runes.
- Hel's Road is here: tick it on the Re-weave screen for a one-life run, with extra XP and better quest rewards for finishing level 60.
- A full balance pass: every rune was measured on one scale. Epic runes that were far too strong or weak moved toward the middle, Common to Rare runes add less on their own, and two or three copies of an Epic are meant to be about twice and four times one copy.
- Control is much lower, most of all early on, and a fully built control setup holds an enemy for about 20 seconds at most.
- Rune slots open later and further apart, at mastery 20, 40, 65 and 85.
- Epic runes have a third-copy effect, and a shared copy counts as a copy.
- PvP control is real: half length, then short immunity, never longer than 20 seconds on a player.
- Gungnir's Mark is a new Legendary rune, and Multishot a new Rare rune; Twin Cast is now called Multicast.
- Runes shared to other abilities show as greyed squares, the Abilities panel has a search box, and runes you take off an ability come back when you put it on again.
- Joining a game now also checks the mod's files, and Hel's Road deaths are a dropdown in Settings.
- Hel's Road is here: on the Re-weave screen you can tick it for a one-life run. A kill by a creature, boss or player ends it (a server setting can make any death end it); finish level 60 without being killed for a permanent +10% XP per finished run, and quest rewards roll one tier higher while you walk it.
- Fixed: a kill by another player (or their summon) now ends a Hel's Road run even with PvP on, as the setting text says.
- Hel's Road: the Easy / Hardcore choice is now a dropdown on the Server rules tab of Settings. The host can change it there; other players see it read-only. On a dedicated server it is set in the server's config file.
- PvP control is real now: with the PvP setting on, stuns, roots, sleep, fear, silence and the rest work on players at half their normal length, followed by 5 seconds of immunity (the old Slow-only rule is gone; the setting "Hard control immunity seconds" replaces the Slow settings).
- In PvP no control on a player lasts more than 20 seconds, however many bonuses it has.
- Balance pass: every Common to Legendary rune was measured on one scale and adjusted. Epic runes that were far too strong or weak were brought toward the middle (Holy-Sworn, Water-Sworn, Earth-Sworn, Steel-Sworn, Steam Veil, Mending Burst, Circling Runes, Deep Draw, Void Rift, Held Word, Siphoning Rune). Common to Rare runes now add less on their own, most of all Echo, Downpour, Fork, Split, Bounce, Cone and Nova, because low-level builds were too strong. Two and three copies of an Epic are meant to be about twice and four times one copy.
- Control is lower, and early control is weakest: Binding Roots roots for 1.75 seconds (was 10) and Word of Stillness stuns for 1 second (was 3), with later abilities nearer their old lengths. Sleep-Thorn sleeps one and a half times as long (was twice), the Controller role bonus is half as large, and Deep Draw no longer lengthens control. A fully built control setup holds an enemy for about 20 seconds at most.
- Rune slots now open later and further apart: the second and third normal slots at mastery 20 and 40, the Epic slot at 65 and the Legendary slot at 85 (before 15, 30, 50 and 100). Slots you already have are kept.
- Drowsing Field now lets burning and poison enemies fall asleep: damage-over-time ticks no longer count as being hurt.
- Damage-over-time ticks (Burning, Poison, Venom, Bleeding and the rest) no longer wake a sleeping enemy.
- Fixed: Returning Haft with Echo no longer starts a whole new repeat on every pass; the card's one repeat per cast now holds.
- More rune pairs now work. Twin Strike takes Multistrike (each hand hits a different enemy) and Pull. Great-Shield Wall takes Wide (a wider wall and more cover), Lingering (the wall holds 2s after you stop blocking). Call Back takes Haste (a faster channel), Wide (30 HP to allies near the revived one) and Delay (a later revive at higher health). Wolf Form takes Lingering, Battle-Fed (kills add time) and Bounce (each bite also makes another enemy Bleed). Bear Form takes Lingering, Pulsing (enemies it hit are Taunted again every 3s) and Wide (a 5m swipe).
- Many more rune pairs now work, for example on Rise, Warding Wall, Trapper's Cache, the stances, Weapon Imbue, Summon and the songs.
- Dodge-Loosed and Shield-Loosed now work on the three songs and on Weapon Imbue (a dodge or block turns Imbue on, never off).
- Reach now lengthens the range of Boon, Warding Rune, Mending Touch, Dread Howl and Heavy Limbs by 20%.
- Sleep-Thorn works on Weakening Hex: the target falls Asleep for 15s instead of being Hexed.
- Haste works on Rune Bolt: its cast is 12% shorter.
- Nine more runes can now be copied by Borrowed Rune, Greater Borrowed Rune and Shared Sigil: Beam, Seeker's Point, Carried, Undertow, Spellblade Echo, Turning Hue, Prism Shift, Pull and Kinship. A shared rune that an ability already holds counts as its second copy, where the rune stacks.
- Multicast, Multistrike and Multishot now add exactly one more cast, strike or shot per copy, in any slot (one Multicast casts a spell twice, two copies three times). A single Multistrike or Multishot is now 2 strikes or shots, where before it was 3.
- Twin Cast is now called Multicast, and each copy adds exactly one more cast (like Multistrike and Multishot).
- Turning Hue now lends its element to your next cast (two casts with a second copy, three with a third) instead of reading your past casts.
- Gungnir's Mark: the rune's own symbol shows over the marked enemy's head (only you see it), shots and beams turn much more sharply onto it, copies of a cast reach the mark even past the ability's range, and the beam fired behind you curves up over your head. Four Winds' side beams last as long as the main beam.
- Rise with Beam builds its wall where the beam lands and follows the beam's end as you sweep it. A rune shared to an ability that already holds it shows grey with "This ability already has it, so the copy adds nothing." Fixed: Greater Spare Socket's second Epic slot only accepted Rare runes.
- Runes shared to other abilities (Shared Sigil, Greater Borrowed Rune, Spell Pair, Gifted Rune) now show as a greyed square under the slots of each ability they reach (slots wrap to a second row past six), and Gifted Rune says "Gifted to you by an ally" on the ally's panel.
- Epic runes now have a third-copy effect, and six more Epic runes (Seeker's Point, Carried, Undertow, Spellblade Echo, Turning Hue, Prism Shift) have second and third copies. A shared copy counts as a copy, so an Epic can reach three copies; one share per ability for Epics, and Common to Rare runes stack without a limit.
- Epic runes print their final number; a slot no longer raises them again (only Charges still does). Sworn Runes follow their cards, Void Rift keeps each burst, Heavy Hand's pause counts from when it is ready, and Pulsing only repeats on its own target.
- Spell Pair's copy of a rune that cannot be copied shows a red square and does nothing.
- The Abilities panel has a search box.
- Abilities that leave your bar no longer hold on to their runes: the runes go back to your pile, and when you put the ability on your bar again it takes back whatever is free and still fits. Fixed: the third utility slot's ability could fall off the bar on every load.
- An ability that leaves your bar now ends its imbue, stance, form or mount and frees its eitr reserve; a Summon with runes loses its pet when it leaves the bar.
- Rise, the Rise walkway and Warding Wall stones now look like the material: the game's own rock, iron for Steel, ice for Frost, and tinted stone for the other elements. Wall stones are solid. The Rise walkway drawn with Beam is a row of upright stone blocks locked to the nearest ground.
- Joining a game now also checks the mod's files: an edited copy at the same version number is refused with a plain message.

## 0.2.1673 (beta)
- PvP is here as a server setting, off by default: hard control becomes a short Slow, ability damage to players is 40% by default, and player kills give no XP.
- Everyone in a game must now run the exact same Fate Woven version; a different version can't join.
- Damage bonuses and damage-taken cuts now apply to spell damage as their cards say, so spell builds feel stronger.
- Hel's Leech triggers far more easily: a Bleeding enemy busy with someone else counts as unaware.
- Spell Pair also copies the rune in the element slot, as its card says.
- Trapper's Cache sets its trap right in front of you instead of at the crosshair.
- Hearth Shelter's hut darkens at night and its fire is fully purple-pink.
- Your pet now stays with you through death, with no second pet after a respawn.
- Co-op is smoother with far fewer network messages, and effects that end later now fire on time on other players' enemies.
- The first casts of Summon, Rune Bolt and Hearth Shelter no longer stutter.
- New server setting "Fate Woven PvP" (off by default): when it is on and both players have Valheim's PvP switch on, Fate Woven abilities can hurt each other. Hard control becomes a short Slow on players, our ability damage to players is 40% by default ("PvP damage %"), killing a player gives no XP or kill effects, and a PvP death skips the death penalty and doesn't end a Hel's Road run. Pets and thralls of the other player take the same cut.
- Everyone in a game must run the exact same Fate Woven version; a different version can't join. (Before, it only warned within 0.2.x.)
- Co-op is smoother, with far fewer network messages for moving spell effects, stacked statuses, short ally buffs and totem heals.
- Old saves now rename merged runes in drafts that are waiting, too.
- Co-op "when it ends" effects (Root Rune, Drake Rune, Valkyrie's Strife, Dread Howl's Pull) now fire on time on enemies another player's game runs.
- Spell Pair now also copies the rune in the ability's element slot to the next ability, as its card says.
- Trapper's Cache now sets its trap right in front of you instead of at the crosshair. Hunter's Tether still puts its trap under its enemy.
- Hel's Leech: a Bleeding enemy that's busy with someone else counts as unaware, so it triggers far more easily.
- Damage bonuses and damage-taken cuts now apply to spell damage as their cards say (the Boon's spell bonus, blessings' cuts and more). This makes spell builds with these bonuses noticeably stronger, and spell-damage cuts noticeably tougher.
- Your pet now stays with you through death. Before, a respawn could call a second pet and leave the old one in the world.
- Hearth Shelter's hut darkens at night like the world around it, and its fire is fully purple-pink.
- The first casts of Summon, Rune Bolt and Hearth Shelter no longer stutter, because they are loaded while the world loads.
- Fixed a harmless error in the log when logging out, and the first spell right after a teleport now aims correctly.

## 0.2.1631 (beta)
- Co-op: Root Rune's and Drake Rune's end effects now work on enemies another player's game runs.
- Co-op: Thornroot and Dread Howl's Pull now catch enemies another player's game runs.
- Co-op: Valkyrie's Strife waits until the control ends, on any player's enemies.
- Co-op: Drowsing Field from another player keeps enemies asleep, and the first hit on a sleeper deals double.
- Co-op: Draugr Rot's faster Venom and set-bonus status durations reach enemies another player's game runs.
- The Great Sea-Wall now protects allies inside it too.
- Damage cuts from Song Beneath the Shield, the Sea-Wall and "enemies deal less" effects now cover every damage type.
- Thrown Voice tells you where your cast came from, and gather quests count every matching item at the hand-in.
- These now work on enemies another player's game runs: Root Rune's and Drake Rune's end effects, Thornroot, Dread Howl's Pull, Draugr Rot's faster Venom, and Valkyrie's Strife (it now waits until the control ends).
- Drowsing Field cast by another player keeps enemies asleep between pulses, sends far fewer network messages, and the first hit on a sleeper deals double for everyone.
- Set-bonus status durations now apply on bow and weapon hits against enemies another player's game runs.
- Ash Veil and Stormshade make enemies lose track of covered allies more reliably.
- The Great Sea-Wall now cuts damage for allies inside it too, for every damage type.
- Song Beneath the Shield's damage cut, and the "enemies deal less" effects (Fimbulwinter, Níðstang and similar), now cut every damage type.
- Thrown Voice tells you where your cast came from (the nearest summon, totem, wall or pillar), or that it came from you when nothing is within 30 m.
- Gather quests count every matching item you carry when you hand in.

## 0.2.1617 (beta)
- Carried Threads: after a Re-weave, the ability and rune you carry over wait in a second window under your draft, and you still make one pick.
- The top quest rewards are now called Legacy Rewards, and the Compendium and first-time hints are rewritten in plainer words (hints cut to the ten that matter).
- Hearth Shelter's hut is rebuilt: one wall high under a sloped roof, ghostly and element-tinted, with a purple-pink fire and no smoke.
- Many cards now do exactly what they say: all Epic and Legendary runes, ten set pieces, and the Steel, Shout and Hel's Leech wording and rules.
- Effects that fire "about N times a minute" on rare events now fire as often as their cards say, so they are noticeably stronger.
- Control on big enemies lands at once at half length; only bosses use the hidden meter. Crossbows count as bows.
- Co-op: heals, statuses, auras and "allies" cards now reach other players, and several crashes and desyncs are fixed.
- Saves are safer: a damaged card file or an older version no longer removes cards, and a backup is kept.
- New setting General > Logging (Quiet, Normal, Detailed) and a repeat limit for warnings, for easier bug reports.
- Everyone in a game must update together: card data changed, and many co-op effects need the new version on every player's game.
- Compendium entries now open as you meet each thing in game, including three new ones: quests and Charms, Re-weave, and Legacy Rewards.
- Epic Loot's choose-one-of-three now offers up to three items, with their rarity colours on the buttons.
- The permanent top-tier quest rewards are now called Legacy Rewards everywhere (they were called Uniques). The Mastery list, the reward messages and the first-steps text use the new name.
- Re-weave now gives you Carried Threads: the ability and rune you pick on the Re-weave screen wait in a second window under your draft, also called Carried Threads, instead of being handed to you for free. You still make one pick, and anything you pass over stays there for the next draft of that kind.
- Hearth Shelter's hut is rebuilt: its walls stand on the ground, one wall high, under a sloped roof, and its bed lets you sleep. It now looks ghostly, with see-through walls tinted in your ability's element colour, faint white-gold runes on the walls, drifting sparkles, and a fade-in with a burst of sparkles when you cast it. The fire is purple-pink and gives no smoke, so you aren't Smoked inside. You still can't walk through the walls.
- Sleeping through the night no longer removes the hut, portals, temporary workbenches or the Traveller's Trunk.
- Drowsing Field holds sleepers on enemies another player's game runs, and no longer keeps immune enemies immune.
- A message tells you when another player in your game runs a different Fate Woven version.
- Cooldowns now carry on after you log out and back in. Dying still resets them.
- Co-op: kills near the world spawn on a dedicated server now give XP and quest credit.
- Co-op: heals from other players now get your healing bonuses, and Trickster's Ante's -60% applies to them.
- Co-op: many effects now work on enemies another player's game runs: Blind, Soothe the Wild, Beast-Speech, pulls and Water Melee's push, Fimbulwinter, Níðstang and Wraith Shroud-Thread's damage cuts, Hel's Harvest, Calmer of Flame, Cowing Tremor, beam holds, Drowsing Field, Weakening Hex's bounce, Battle-Fed and Crimson Tide.
- Co-op: the Vanir springs wash Burning and Venom off other players too, and Rune-Tether won't take a cart someone else is pulling.
- Nine Nights, Gold-Toothed Vigil and beam ticks work the same at any frame rate.
- Smoother frames and less network traffic in co-op.
- Cards that say "allies" now reach other players, not just you and your tames.
- Co-op: Avenger's Debt and Hringhorni's Pyre work when a player dies in another player's game, and one song at a time holds for allies. A crash from Blinding Glare when you joined a host is fixed.
- PvP: when someone with PvP on swings at someone with PvP off, side effects such as Shared Hide moving damage onto a thrall, Brace's Blood Shield healing, and Boon lifesteal no longer happen, and another player's game can no longer stagger you.
- Ash Veil and Stormshade now reach allies standing inside them, other players too: enemies lose track of them, and Ash Veil stops ranged hits on anyone inside, you included.
- Fading Veil now gives stealth to other players, and it ends when they attack.
- Save safety: a damaged card data file, or going back to an older version, no longer removes cards from your character; if your Fate Woven data can't be read you're told, and the original is kept as a backup; unreadable Traveller's Trunk contents are kept as a backup too.
- Cards that were cut or renamed no longer disappear from old saves. A cut Carried Thread waits in case the card returns and doesn't count toward your 10, and if your Full Set was cut you can choose a set for stage I again.
- New setting General > Logging: Quiet, Normal or Detailed. Set it to Detailed before reporting a bug and attach the log. The same warning no longer fills the log: after 5 copies it shows a "(repeated N times)" line instead.
- The last four set element runes now do what they say: Stag Rune (your next hit on a Shocked enemy also Staggers it), Ooze Rune (Venom stacks to 15), Lox Rune (enemies you Stagger are knocked back 2 m) and Ember Rune (Burning stacks to 80%). Each works while the rune is on your bar.
- Ember Rune and Ooze Rune now help slow abilities too: with Ember on an ability that has a cooldown of 5s or more, Burning starts at 80%; with Ooze on one with a cooldown of 8s or more, each hit adds 5 Venom stacks at once.
- Gathered Bolt's element status now lands from half charge up (a quick tap still doesn't), and the card says so.
- Effects that fire "about N times a minute" on rare events (kills, blocks, casts and slow ability hits) now fire as often as their cards say. Some were firing far less often, so these effects get noticeably stronger.
- Control on big enemies now lands at once at half length, then 6 seconds of immunity, instead of needing several hits to fill a hidden meter (bosses still use the meter). Bosses are Slowed at once by Binding Roots and Rooting Shot.
- Crossbows now count as bows on every card that says Bow.
- Steel abilities now use your held weapon's damage type, as the Steel card says.
- Stagger effects now fire on every stagger you cause: Lox Rune, Antler, Silt and Surge, Hel's Sickbed, Edge-Song and Thor's deed.
- Every element's status now lands where its card says, for example Fire Roar, Hex, Heavy Limbs and Glare burn, Earth staggers and Steel Sunders. Finisher's Mark now doubles.
- Hand Between the Jaws costs nothing when no enemy is in reach.
- Steel now follows your weapon: maces, sledges and fists deal Blunt, with extra stagger, and stagger instead of causing light Bleeding. Steel's +10% damage and +15% stagger now apply.
- Yew-Hall Draw's +8% speeds up crossbow reloading.
- Reaper's Toll refunds about 6 times a minute, as its card says. Every cast that finds no target refunds its cost and cooldown. Arcane Finisher's Mark no longer applies Spellbound.
- Statuses that come from an ability's zones, puddles, rings and spreading effects now count as that ability's, so set bonuses and runes that lengthen statuses or add stacks reach them too.
- Beams now build a ramp per target with a half-second grace, and a Warding Rune on a beam adds a shield on every tick (shields still stack only up to the shield cap).
- Card wording now says what the cards really do in several places, for example Shout blessings fire only on Shout, Challenging Roar and Dread Howl; Weapon Imbue affects plain weapon attacks only; Call Back works within 60 seconds of a death; Death's Door only from above 25% health; and "elite" means a starred enemy or a boss.
- Add-on API: RegisterElementStatus lets another mod's element apply a Fate Woven status.
- Ten rune set pieces that did nothing now work: Neck Scale, Shaman's Herb, Leech Tooth, Wolf Fang, Abomination Root, Growth Tar, Serpent Fin, Bat Wing, Forge Slag and Charred Relic. Charred Bone, Valkyrie Feather and the Ember Ash and Bloodsworn 5-piece bonuses work too.
- Valkyrie's Choice's full set tooltip now says it heals 10, as it does.
- Legendary runes now do everything their cards say: Void Rift, Web of Fate, Giant's Guile, Mead-Hall Oath, Iron Ledger, Trigger Bolt, Spell Pair, Grove-Keeper's Vow, Hound's Watch, Witch's Familiar, Wolf-Warrior Bond and the fit rules for Blood-Price Edge, Spirit Relay, Fate-Thread Mending and Star-Carrier.
- Card wording fixes: Trigger runes and Riding Spell say a signature in the next slot is cast; Harmony and Mead-Hall Oath's pass-on are songs only; Swarm Fletching needs an enemy hit; Void Rift opens where the shot lands or runs out; Undying Ward shows how long it has held.
- Undying Ward now shows a counter above the food icons for how long its shield has held, up to 60 seconds.
- Void Rift now opens where a shot stops or runs out, or at an area's centre a moment after the cast if it hit nothing, one rift per cast.
- About 50 Epic runes now do everything their cards say, including Hobbling Blow (no running or fleeing, +25% Stagger taken), Volatile (survivor buff, rush and recast detonate, a second copy that speeds up resummoning), Duelist's Focus, Steam Veil, Thornroot, Drowsing Field (sleepers stay asleep), Rampart of Spite, Rot-Bloom, Stormshade, Last Command and many second copies.
- Card wording fixes: Circling Runes orbit for 3 times the flight time; Unbinding no longer mentions an enemy buff that doesn't exist; Arcane Expose counts as Spirit damage; Shared Hide's second copy sends 50%.
- The rest of the Epic runes now do what their cards say, including Thrown Voice, Turning Hue, Echoing Rune, Hel's Leech creatures, Frost-Sworn wolves, Dodge- and Shield-Loosed, Ash Veil on area casts, Hobbling Blow on stance and imbued swings, and the second copies of Eruption, Black Ice, Drowsing Field, Totem Vessel, Running Draw, Skyward Arc and Ward-Breaker Blow. Seeker's Point, Quake Knuckles, Skyward Arc and Raven-Guided fit the abilities their cards say.
- Hel's Leech now works: crouching out of an enemy's sight counts as Stealthed, and the hit that makes an enemy Bleed counts too.
- Fixes: Hel's Leech, Skadi's wolves, Eruption, Running Draw, Drowsing Field and Black Ice now work as their cards say, and the hut's runes show on worn walls too.
- The in-game Compendium entries are rewritten in plainer, friendlier words. The facts are the same.
- First-time tutorial hints are cut down to the ten that matter, reworded to be short and friendly like Valheim's own hints, and no longer pop up while the draft page is open. The rest are in the Compendium.
- Lists now scroll with the mouse wheel or the scrollbar only, so dragging no longer moves them.
- Utility abilities that place pieces now put them on the floor when you are indoors, and Waypair's far portal faces the way you faced.
- The moving shimmer on signature ability icons is turned off, because it smeared across the art.

## 0.2.1490 (beta)
- Heals now show white-gold motes around whoever is healed, and everyone nearby sees them.
- Undo after a Re-weave keeps much more: favour, quest history, blessing offers, Full Set pieces and the higher Charm.
- Full Set pieces survive a Re-weave, and unopened blessing offers are refunded.
- Long Banner now boosts every summon except totems, and their ranged hits too.
- "Clear a location" quests work on someone else's server.
- Blessing auras reach your allies with less network traffic, and spell effects go only to players within 80 m.
- Eitr Flow also speeds food eitr regen, and Spell Edge no longer boosts pets.
- Max health, stamina and eitr bonuses now apply to the whole total, and several stat bugs are fixed.
- Switched-off cards, runes and Uniques no longer leak into drafts and rewards.
- Please update together: older players miss newer players' blessing auras.
- Every Fate Woven heal now shows the same white-gold motes rising around whoever is healed when they were hurt (at most once every half second each), and everyone nearby sees them. Regeneration at full health and health-cost refunds show nothing. Meads and other vanilla heals are unchanged.
- Spell effects (heal motes, bursts and beams) now go only to players within 80 m, and blessing auras use even less network traffic, so big servers send less.
- Blessing auras (Saga, Sigr, Valhalla's Doors, Hallow and Fensalir) now reach allies with less network traffic on busy servers, at the same strength, reach and timing. Your own tamed animals now get your auras too.
- "Clear a location" quests now work for a player on someone else's server, and the quest board fills again for a character coming from another world whose day count is further on.
- Please update together: 0.2.1468 and 0.2.1490 can join the same game, but a player on the older version won't receive a newer player's blessing auras (Saga, Sigr, Valhalla's Doors, Hallow and Fensalir), and "clear a location" quests need the server on the new version too.
- Undo after a Re-weave now keeps your favour, boss kills and quest history, blessing offers and the blessings you paid for since, token maxes won since, Full Set pieces, and the higher Charm (tier first, then quality).
- Full Set pieces are kept through a Re-weave. A Re-weave refunds the favour of unopened blessing offers that cost favour (free offers from quests aren't refunded). A boss whose trophy a Re-weave reset offers its trophy again on the next kill.
- Eitr Flow also speeds food eitr regen. Spell Edge no longer raises pet and summon damage (Long Banner is their boost; totems still count) and now also raises Binding Roots' damage.
- Elemental and Greater Charms keep the +5% per upgrade of the Charm they're on, and an Elemental Charm counts its own tier for Hearth Shelter's wall health and the Bots.
- Long Banner now covers every summon except totems: decoys, signature, duo and blessing summons, and the pet pack's bodies, as well as the Summon pet and Thralls.
- Long Banner's damage boost now also reaches the pet's ranged bolts and the summoning signatures' hits, not just their health.
- Fixed: percentage bonuses to max health, stamina and eitr now apply to the whole total, and several flat bonuses (Goat-Bone Feast, Evergreen Vigor, Stag Stance, food, the Wells) were missing some multipliers before.
- Fixed: Cave-Bear Stance's 25% slow now applies, reservations no longer cut normal food eitr regen, and Deep Reserve's refund counts when checking whether you can reserve.
- Cards, runes, blessings and Uniques that a server switched off no longer turn up in drafts, rune stones, quest rewards or lock-ins. A Full Set stage waits, instead of being lost, while one of its pieces is switched off.
- Fixed: the "Replace your Charm?" popup closes when you die or the crafting window closes, and Yes only crafts while you're at the open station. The Re-weave screen closes on death.
- Fixed: a totem plant is interrupted if you're moved more than 3 m by a knockback or teleport, and the Hel's Road switch no longer says "hardcore" on an Easy server.
- Card text fixes: Fate's Pity III no longer promises a Rare on every roll; Seventh Slot, Patron's Favour, Light Foot, Lucky Drafts, Lucky Runes, Lucky Quests and the Elemental and Greater Charm descriptions now say exactly what they do. The first-steps text no longer says bosses give a reroll token.
- The Unmaking Unique reward was removed (it did nothing, since taking runes out of an ability is already free).
- The Infested Mine quest now finds its place (it was skipped before).

## 0.2.1468 (beta)
- Re-weave: at level 60, start your build over for lock-ins. Pick one ability and one rune that join every later run. An Undo button in Settings works in the beta.
- Charms are one at a time: you hold a single Charm and it can't be dropped or stored. Elemental and Greater Charms move into a Charms list in the Mastery screen.
- Quests follow the Charm you wear, and easier quests pay XP only.
- Rerolls, banishes and locks have a maximum and a current count, with a Clear banishes button.
- Uniques: a list of permanent quest rewards in the Mastery screen, and Epic quests on the board (clear a place) that can pay them.
- The ability bar now grows from 3 to 6 slots at levels 10, 25 and 40.
- Healing, shield and stamina casts have their own rims, and Twin Cast and Split now fit beams.
- Totems are now carved wooden posts with an element-coloured inlay.
- Better with other mods: SeneaL UI, Epic Loot (Warfare gear in quest rewards) and CLLC (quest elites roll their level).
- Many fixes from a full QA pass.
- New: Re-weave. At level 60 the Runes panel has a Re-weave button: you start your Fate Woven progress over and keep your world, gear, skills, favour, special charms and trophy signatures. You pick one ability and one rune to lock in, which join you in every later run, and your rerolls, banishes and locks refill. An "Undo last Re-weave" button in Settings works until level 5 of the new run (on in the beta). Servers can switch it off.
- Rerolls, banishes and locks have a maximum and a current count, and quests are their only source: a boss's first kill no longer gives a reroll, and a Black Core no longer pays for a banish. A new Clear banishes button on the draft screen brings every banished card back at once, with a warning that it isn't selective.
- Hel's Road (off by default, with the end-game switch): an optional hardcore Re-weave. One life, Easy or Hardcore deaths as a server setting, and a permanent +10% XP for each run you finish at level 60. Quest rewards roll one tier higher while you walk it.
- You can hold only one Charm at a time, and a Charm can't be dropped or stored in a chest. Crafting a higher one asks first before it replaces the old one.
- Elemental and Greater Charms live in a Charms list in the Mastery screen (or right-click the worn Charm). You switch your Charm into a special form from there, and a Re-weave never loses them.
- Quest notices follow the Charm you wear, and a notice below the tier of the Charm you hold pays XP only.
- A Uniques list in the Mastery screen shows your permanent Unique quest rewards: stat wells, eitr flow, move speed, Rune Finder, longer buffs, Quick Study, damage and cooldown boosts, Early Slots, a pet boost, Patron's Favour (click a god in the Favour list), Fourth Loadout, Fourth Card (a fourth draft card), Seventh Slot, the Third utility slot, and Full Set I to III (pick a rune set and its pieces go into your Runes panel).
- The ability bar grows as designed: 3 combat slots at the start, one more at combat levels 10, 25 and 40. Characters above level 10 get their extra slots when they load. A message says when a slot opens, and the new key settings Slot7 and Utility3 are unbound by default.
- Epic quests are on the board: kill a number of enemies at a named place 150 to 2000 m away (the Burial Chambers, Sunken Crypt, Frost Caves, a Fuling village, an Infested Mine or a charred fortress). They can pay a Unique.
- Epic Loot quest rewards: a "choose one of three" gives three different kinds (weapon, armour or shield, jewelry or trinket), rewards show Epic Loot's own names and colours, and Warfare gear is included when both mods are installed. With Hel's Road or Lucky Quests, a boosted Legendary roll can give Epic Loot's Mythic and Ancient rarities.
- With CLLC installed, a named quest elite gets CLLC's own level, infusion and extra effect.
- Beams no longer twist round each other when several run the same way: the helix look was removed, and they run side by side.
- Totems are now a carved wooden post, 0.75 of a person tall, with its own art for the Support Totem, War Totem and Totem Vessel, an inlay glow in the element's colour, and a soft glow so it shows at night. The old guard stone and Fuling pole looks are gone.
- The key-clash warning also reads keys other mods keep as text, such as Epic Loot's ability hotkeys.
- Charms put in containers were deleted on load.
- A Flametal Charm made every quest XP-only.
- Re-weave lost the trophy drafts, and Undo lost the Full Set choices.
- "Clear a location" quests paid one kill's XP.
- Full Set gave runes the server had turned off.
- Deep Reserve raised max eitr when it shouldn't.
- Patron's Favour also drained the rival god by the bonus.
- Hel's Road's death message was hidden and its killer was wrong.
- The Fourth Loadout button showed after relogging.
- "Clear a location" quests don't work for a client on someone else's server.
- Long Banner covers only the Fylgja pet and Thralls.
- Healing, shield and stamina casts have a rim: soft white-gold for healing, blue for shields, yellow for stamina. Damage casts have none. Healing beams pulse toward the target, and ally cones and novas get a rim outline.
- Rains show a healing rune (Berkanan) or a damage rune (Thurisaz) in the middle of their rune circle, and other players see it.
- Stamina from a Shout shows as yellow motes on each player it reaches.
- If one of our keys is also used by another mod (for example Z, B, H and Left Alt with SeneaL UI, Equipment and Quick Slots or Quick Stack), a message lists the clashes once. Our defaults stay; rebind either side in the config.
- Twin Strike works with a dual-wield weapon: it counts as both hands, two hits at 80% each. Fixed: Twin Strike had no reach and never found a target.
- The Bots' damage, the Summon's HP and the Hidden Hall's size follow the Charm you wear. Charm tooltips say so.
- Fixed: Chant of Many Wards no longer lowers a bigger Shout or totem bonus from another player, and an older 0.2 game no longer loses the bonus. Ragnarok's Sentinels outlines a close enemy over a far one.
- Fixed: a shield break effect could linger about 90 seconds after a shield timed out.
- A held beam or a charged draw no longer recompiles the ability every frame. A held Wide beam ran about 20% faster in our tests.
- New: Elemental and Greater Charms, rewards from Legendary quests. Elemental Charms boost one element; Greater Charms go above the Flametal Charm (odds 60/30/10 for I, II and III). Their slots show the tint as a border (element colour, or gold for Greater), and the fill turns orange while worn.
- All seven pinned quest hunts now have a named elite at the pin: Grath the Troll, Vorn the Abomination, Krell the Stone Golem, Brug the Goblin Brute, Dunn the Gjall, Ashk the Morgen and Torv the Fallen Valkyrie. With CLLC installed, it rolls its own level, infusion and effect. The brute chief quest now asks for one brute.
- More blessings now work for your allies and other players, as their text says: Njord's Stillness, Brightness Returned from Hel, Apples Shared, Feast-Host, the Cauldron for others, Bristles of Gold's glow, crop growth, The High Seat and Mistletoe for allies, and Spear Flung's stamina. 18 blessings that fell short of their card were fixed.
- Ragnarok's Sentinels shows enemies as a red outline through walls. The High Seat's Watch shows a gold-white flash over the enemy's head and a chime before its attack lands.
- Chant of Many Wards and Spell-Woven Mantle work. A second aura of the same ability needs Chant of Many Wards.
- Trickster's Ante counts blessing hits, and Belt of Might Unbuckled arcs on ability hits. Youth-Apple Verses reaches allies. Thunder-Stone Ward says it rises every 30s in combat.
- Blessing hits now scale with their own element. Gjallarhorn's Warning shows an on-screen arrow. Champion's Ring and Horn at World's End work on any Shout ability.
- Fixed: Valhalla's Feast and Horn of Mead buffs arrived empty on other players' games.
- Shields are layers, each with its own timer: a short shield no longer cuts a long one short. At the cap, a new shield adds nothing.
- Summon Mount's element runes work: Lightning runs faster, Fire leaves a fire trail, Water walks on water, Nature climbs slopes up to 50% steeper, Shadow makes you harder to notice.
- Other players saw your Wolf, Bear or Raven Form as your normal self.

## 0.2.1467 (beta)

## 0.2.1415 (beta)
- One shape rune per ability (Cone, Nova, Beam, Downpour), one Trigger rune on your whole bar, one Path rune per ability (Drifting, Zigzag, Wild Path) and one Cost-change rune per ability (Kindred Blood, Duelist's Focus). A second one will not socket, and the socket says why. Old saves keep the first rune and grey out the second; nothing is deleted.
- Twin Cast, Split and Four Winds fit Beam. Twin Cast's beams twist round each other on one line, and beams running the same way at once twist into a helix.
- Rune combinations: about 80 cases where one rune silently cancelled another now both work (Downpour, Drifting, Beam, Wide, Twin Cast, Split, Echo, Four Winds, Borrowed Rune, Focus and Kingstone on Legendaries and more).
- Downpour works with Twin Cast (two rains side by side) and Split (a rain that ends splits into two smaller ones).
- Extra casts (Echoing Rune, Four Winds, One Voice, Ring-Giver, Totem Vessel, echo recasts) now scale their shield, hex weakening and buff share at their share. Delayed and echoed beams also scale percentage heals, buffs and stamina.
- Illusion casts no longer trigger Web of Fate (like the other trigger runes).
- A second copy of a "One per character" card shows a red "No additional effect" and does nothing (Focus counts once).
- Beams rebuilt: a beam casts without a target, straight out from your hands along the crosshair, and stops at the first enemy or wall. Steel's pierce passes it through more. Homing (Raven-Guided) bends it smoothly onto targets, Four Winds' side beams too.
- Beams are drawn as glowing round tubes, much easier to see. Wide makes a big soft tube, Twin Cast's beams run side by side, and sparks show where a beam hits.
- Heal and buff beams never affect the caster (Mending Touch, Warding Rune and Boon beams).
- Effects on wisps and Steel pets, and in Wolf, Bear and Raven Form, no longer vanish. Glows and buff sparkles no longer disappear for good.
- Ghost copies of totems and weapons show one model.
- Co-op: lasting effects (Raven Banner ravens, Dvergr Lantern, long zones) no longer vanish for other players after 2 minutes. Zone rings show their element colour to other players, and spell orbs show at their real size.
- Altar of the Gods: a rune stone laid down as the table, with a new sigil plate on top.
- With Epic Loot installed, quests can reward Epic Loot items, a choice of three items, and dust, essence and reagent bundles.
- With CLLC installed, quest elites get CLLC's own level, infusion and effect. The Old Tusker is now a named elite boar.
- The Quest board works on dedicated servers.
- Charms upgrade like vanilla tools, up to quality 4: each level adds 5% to the charm's strength. An upgrade takes the recipe again, except its first item (the boss token, needed once).
- With SeneaL UI loaded:
- With Equipment and Quick Slots or Extra Slots, the Fate Woven button bar moves under the crafting panel, so their equipment panel shows.
- Path of Valheiman: our spells keep their average strength.
- The buff row above the food icons shows only stances, Weapon Imbue and timed self-effects. Buffs and shields show once, in the normal status row.
- Timed shields fade just before they come back: Nine-Mothered Guard's shield, the Support Totem's Holy shield and Shield-Ship Crossing's shield now last a little less than the time between them.
- Hugin the raven brings Fate Woven's tips, as vanilla's tutorials do (still off by default).
- The Holy pet always claws (it could keep a taunt that never hits).
- A respawn after death no longer loses track of a pet that is still out.
- The Flametal Charm could not be made (its recipe named the wrong item).
- The Echo card's switch now works.

## 0.2.1374 (beta)
- A pale-blue shield bar sits on top of the health column while you have a shield.
- The shield bubble is faint again: a shield renewed on a timer no longer piles up extra layers until it glows bright.
- Nine-Mothered Guard's shield lasts 17s, so it fades just before the next one.
- Dropping a blessing on an active slot replaces that slot's blessing. One blessing per god still applies, and the screen says which one was replaced.
- The Arcane pet (Dvergr mage) no longer casts vanilla's shield bubble; pets only use Fate Woven's attacks.
- The Quest board window's title no longer sits behind its tabs.

## 0.2.1364 (beta)
- New: the Quest board is two boards stacked, with notices and wanted posters pinned on it.
- New icons for the Quest board and the Altar of the Gods.
- Quest notices match your world's progress: their biome is the one after the highest boss beaten in your world (Meadows before Eikthyr, then the Black Forest, and so on). Your level no longer decides it.
- Unique abilities: Summon can be in only one bar slot at a time. Extra Summons stay in your book with their own runes; drop one onto the slot to swap.
- The Runes panel updates as soon as you put a Charm on or take it off.
- A quest board takes down any notice for a biome your world hasn't reached yet and puts up new ones.

## 0.2.1354 (beta)
- Pets fight enemies within 20 m of you (it was 10 m).
- Caster pets now shoot a visible Fate Woven bolt.

## 0.2.1352 (beta)
- Pets and summons use only Fate Woven's attacks: their creature's own slams, area blasts, projectiles, statuses and knockback are gone.
- Pets, their pack copies and your mount never damage trees, rocks, ore or buildings.
- A pet you haven't named gets a random name.
- The stamina number sits under the stamina bar and the eitr number above the eitr bar, so neither covers the reserved eitr.
- The Favour list sorts gods by rank, then by progress in the rank (issue #12).
- Cooldowns over a minute show minutes, such as "4m" (issue #13).
- A utility ability's rune lines say what that rune does on that ability (issue #14).

## 0.2.1345 (beta)
- New utility ability: Summon Mount (from level 30). A 5s channel calls a saddled Lox to ride; it never fights. Element runes change it: Lightning faster, Fire a flame trail, Nature higher jumps, Shadow hidden while riding, Water faster swimming.
- The Earth pet is now a stone Golem, and Summon calls it by default.
- Every tank pet (Earth, Steel, Frost) taunts nearby enemies from its first rune.
- Pet damage evened out: tank, healer and support pets about 8 damage a second, DPS pets about 16.
- Pets only fight enemies within 10 m of you, and run a little faster than you sprint.
- The Steel pet fights with its own weapon, in steel.
- Standing near the Fire pet (Surtling) keeps you warm.
- Only the Shadow pet gets sneak attacks; other pets always hit their normal amount.
- Summon's tooltip shows the pet's own hit.
- Blessings: right-click a blessing, or drag it into the reserve window, to take it out; the reserve window has a scrollbar.
- Lists scroll with the mouse wheel or their scrollbar only, never by dragging.

## 0.2.1327 (beta)
- New pet looks: Steel is a polished-steel Charred Warrior with a sword and shield; Arcane a violet Dvergr mage in lavender robes; Nature a moss-green shaman with drifting leaves.
- The Holy Valkyrie no longer has a dark aura; the Lightning wolf is a faint spirit with lightning running through its bones; the Frost golem has an ice texture.
- Everyone in the world sees your pet's look.
- Tank pets are bigger (three-quarters of your height to start).
- Caster pets (Arcane, Water, Nature, Fire) stay back and cast instead of running in.
- Pets no longer talk.
- The eitr bar stays up while you have eitr reserved, and the reserved section lines up with it.

## 0.2.1306 (beta)
- New Epic runes: Mending Burst, Shielding Burst, Wrathful Mend, Mending Ward, Cleansing Burst and Contagion.
- Shields now stack, up to a share of your max health (a server setting, 50% by default).
- New pet looks: Holy is a golden spirit Valkyrie, Lightning a crackling storm-wolf spirit, Frost a small ice Stone Golem.
- Pets on Follow keep following, and no longer die to water or rain.
- Summon and combat toggles earn mastery in a fight and for a minute after; other toggles earn slowly while on.
- Loki's blessings Wolf-Mother's Brood and False Shapes, and his favour for enemies killed by falls, traps or each other.
- Rhythm now makes the ability's next cast cheaper instead of refunding cost.
- Settings are split into tabs. The wheel and the Next / Previous ability keys both work; the Wheel / Cycle switch is gone.
- The ability wheel is carved stone.
- Tooltips: each rune shows once with its count (x3), and runes whose effect is already in the numbers have no extra line.
- Fixed: typing E in a search box closed the inventory.

## 0.2.1288 (beta)
- Twin Cast: the bolts leave your hand together, spread evenly around your aim, and curve onto your target. A lone enemy takes every bolt.
- Spell bolts take a slightly wandering path, so several bolts are easy to tell apart.
- Changing Summon's runes while your pet is out dismisses it. Cast Summon again to call the new one.
- Summon's tooltip says what each element rune gives your pet.
- Toggle abilities (stances, Weapon Imbue, Inner Breath and the toggle utilities) earn mastery while they are on.
- The Blood and Water pets are now Blobs: a red one and a blue one.
- The Earth pet's Lox is a little smaller (you can still ride it).
- Pets on Follow keep following you.

## 0.2.1270 (beta)
- First public beta.
- Fixed: an error every frame after you left a world and loaded another one.
- Abilities that charge (Gathered Bolt and others) now show a charge meter, hold you in place while you charge, and play a casting pose.
- Cooldowns show a large countdown number on the ability icon.
- Ground markers (Downpour and others) are now carved rune circles that follow the ground.
- Tooltips are shorter: they show the current numbers, and the runes you socket change them.
- New: Quests, Charms, the Favour list and the God Altar.

---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
