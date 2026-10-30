# Abilities

[Home](index.md) | [Getting started](getting-started.md) | [Abilities](abilities.md) | [Runes](runes.md) | [Elements](elements.md) | [Statuses](statuses.md) | [Gods](gods.md) | [Sets](sets.md) | [Utility and pets](utility-and-pets.md) | [Interface and multiplayer](interface-and-multiplayer.md) | [Report a bug](https://github.com/processq/fate-woven-issues/issues/new/choose) | [Discord](https://discord.gg/dWC9gWMc)

Every ability costs eitr or stamina and has a cooldown. The element shown is the default; an element rune in the ability changes it.

## Controller

### Binding Roots

*Common | Nature | Target (40m) | 15 eitr | 10s cooldown*

Roots burst under one enemy: it is Rooted for 10s and takes 1 element damage a second while the root holds, and gains the element's status. Bosses are Slowed 40% for the same time instead.

### Blinding Glare

*Uncommon | Holy | Target (40m) | 20 eitr | 20s cooldown*

Dazzle one enemy: it is Blinded (40% miss) for 4s and gains the element's status.

### Dread Howl

*Uncommon | Shadow | Target (15m) | 30 stamina | 30s cooldown*

Howl at one enemy: it is Feared for 6s, fleeing from you, and gains the element's status. Damage after 1s breaks the fear. Bosses lose 20% attack speed for 5s instead.

### Heavy Limbs

*Common | Frost | Target (25m) | 20 eitr | 15s cooldown*

Weigh down one enemy for 8s: it moves 40% slower and attacks 20% slower, and gains the element's status.

### Rune-Chain Grapple

*Uncommon | Steel | Projectile (25m) | 15 stamina | 10s cooldown*

Fire a rune-chain at one enemy up to 25m: it is dragged to you (large enemies half as far; bosses aren't moved), takes 49 element damage and gains the element's status.

### Smother

*Rare | Frost | Target (20m) | 20 eitr | 18s cooldown*

0.8s cast (you can't swing or cast during it): a bubble of the element forms around one enemy's head within 20m: it is Smothered for 3s and cannot move, attack or cast. It takes 6 element damage a second, rising 15% each second. The bubble has a shell of 60 that anyone's hits can break; breaking it ends the smothering and bursts for one second of the current damage. Creatures that don't breathe (undead, spirits, golems, Surtlings) are Blinded for 4s instead (their attacks miss 40% of the time) and take no damage. Large creatures and bosses follow the control meter, as for any hard control. Water creatures are only smothered by Fire, Lightning and Steel. Two smothers on one enemy don't stack; a new one replaces the old. Idea from Richard's son.

### Warding Wall

*Uncommon | Earth | Ground line (10m) | 30 eitr | 25s cooldown*

Raise a 10m wall for 8s. Enemies cannot pass; those touching it take 10 element damage and gain the element's status. The element picks what it's made of, as with Rise: Earth (default) stone, Fire flame, Frost ice, Nature thorns, and so on. Allied projectiles pass through.

### Weakening Hex

*Common | Shadow | Target (40m) | 20 eitr | 30s cooldown*

Hex an enemy for 10s: it deals 10% less damage and gains the element's status.

### Word of Stillness

*Common | Arcane | Target (40m) | 20 eitr | 30s cooldown*

Speak a word of stillness at one enemy: it is Stunned for 3s, unable to move, attack or act, and gains the element's status. Bosses and other stagger-immune creatures are Slowed 50% for 3s instead.

## Healer

### Call Back

*Epic | Holy | Fallen ally (5m), channel | 60 eitr | 600s cooldown*

Channel 3s over a fallen ally to revive them where they fell at 30% HP with 2s of invulnerability.

### Mending Touch

*Common | Holy | Ally (20m) or self | 6 eitr | 6s cooldown*

0.8s cast: heal an ally (or yourself) for 60 HP.

### Warding Rune

*Common | Arcane | Ally (20m) or self | 8 eitr | 15s cooldown*

Ward an ally with a shield absorbing 48 damage for 15s. It doesn't refill: only the Pulsing rune refills it.

## Mage

### Gathered Bolt

*Common | Arcane | Projectile (charged) | 4 eitr | 2s cooldown*

Hold to gather for up to 2s, then release one bolt: 30 element damage on a tap, rising to 90 at a full 2s (+30 per second held). It costs 4 eitr plus 4 per second held. A full charge applies the element's status.

### Rune Bolt

*Common | Arcane | Projectile | 4.5 eitr | 0s cooldown*

0.8s cast (you can't swing or cast during it): fire a rune bolt, a spell projectile (about 50 m/s, reaching about 40m), for 49 element damage. About 12 times a minute a bolt applies the element's status.

## Melee DPS

### Flurry Fists

*Common | Steel | Melee | 20 stamina | 8s cooldown*

A flurry of 6 fast jabs in 1s, each for 40% weapon damage as element damage; About 12 times a minute a jab applies the element's status. Needs Unarmed or a fist weapon: with any other weapon the cast fails.

### Inner Breath

*Common | Nature | Self (hold to channel) | 10 eitr | 20s cooldown*

Hold to channel deep breathing for up to 6s: restore 10 stamina per second. You can't attack or cast while channeling; letting go ends it.

### Leg Sweep

*Common | Steel | Melee | 15 stamina | 12s cooldown*

A low sweep for 60% weapon damage as element damage that knocks the target 4m back (large enemies 2m; bosses aren't moved).

### Massive Attack

*Common | Steel | Melee | 40 stamina | 15s cooldown*

Hold to wind up for up to 2s, then strike: 120% weapon damage as element damage on a tap (a Rune Strike), rising to 300% at a full 2s (+90% per second held). It takes the place of one weapon swing. It takes the combo multiplier of the swing it replaces.

### Rune Strike

*Common | Steel | Melee | 5 stamina | 8s cooldown*

Weapon strike for 120% weapon damage as element damage and applies 1 stack of the element's status. It takes the place of one weapon swing and uses that swing's time, so it never adds a swing. Cast during a swing, it queues as the next combo hit instead of failing. It takes the combo multiplier of the swing it replaces.

### Storm Stance

*Uncommon | Lightning | Self stance (toggle) | 10 stamina | 3s cooldown*

Physical stance (no eitr; only one physical stance at a time): +30% attack speed and dodge rolls cost 30% less stamina, but -15% damage per hit.

### Sudden Impact

*Uncommon | Steel | Melee | 20 eitr | 18s cooldown*

A charged-up strike with any weapon for 60 element damage that Stuns the target for 2s.

### Twin Strike

*Uncommon | Steel | Melee | 20 stamina | 8s cooldown*

With a weapon in each hand, both strike at once: each hand lands its own hit for 80% of its weapon damage as element damage.

### Warrior's Stance

*Uncommon | Steel | Self stance (toggle) | 10 stamina | 3s cooldown*

Physical stance (no eitr; only one physical stance at a time): +12% melee and unarmed damage, and statuses from your abilities last 50% longer; -15% block power while active.

### Weapon Imbue

*Common | Fire | Weapon enchant (toggle) | 20 eitr | 3s cooldown*

Weapon enchant (reserves 20 eitr; one weapon enchant at a time): while on, your weapon attacks (melee, bow, crossbow or thrown) add 12% of their damage as element damage, and about 20 times a minute a hit applies the element's status.

### Wolf Form

*Rare | Blood | Shapeshift (20s) | 30 stamina | 60s cooldown*

Become a wolf for 20s: +30% move speed, and your attacks become bites for 40 element damage that apply Bleeding and the element's status. Other abilities except stances can't be used in form; press again to end early.

## Ranged DPS

### Concussive Shot

*Uncommon | Steel | Projectile | 20 stamina | 15s cooldown*

A heavy shot with your bow, crossbow or thrown weapon for 60% weapon damage as element damage that Silences the target for 4s: it can't use its ranged or magic attacks.

### Longdraw Shot

*Common | Steel | Projectile | 15 stamina | 4s cooldown*

A tap looses a quick shot: 100% weapon damage, which this ability's 0.7 damage scale makes 70% of a plain full-draw shot. Hold to charge for up to 2s more, on top of the bow's own draw, rising to 210% at a full charge (+55% per second held; 147% of a plain shot). Works with a bow, crossbow or thrown weapon; the damage is element damage and applies the element's status.

### Rooting Shot

*Common | Nature | Projectile | 15 stamina | 12s cooldown*

A shot with your bow, crossbow or thrown weapon for 50% weapon damage as element damage that Roots the target for 2s (bosses: Slowed 40%) and applies the element's status.

## Summoner

### Decoy

*Uncommon | Shadow | Self (placed decoy) | 20 eitr | 30s cooldown*

Leave a decoy (with Shadow, the default, a fetch: a hollow double of yourself) with 100% of your max HP - for 8s while you vanish from enemy aggro for 2s. It taunts enemies within 5m; enemies that strike it gain the element's status. Its look comes from its element (Shadow, the default: your shadowy double; Nature: a hare; others later).

### Host of Spirits

*Common | Arcane | Summon (beside you) | 25 eitr | 20s cooldown*

1.5s channel. Call up a host of 3 spirits (30 HP each) for 10s; their strikes deal 15 element damage. They rise as spectral skeletons glowing in their element's colour, with a trail of that element's particles.

### Summon

*Uncommon | Earth | Pet (permanent) | 50 eitr | 3s cooldown*

10s channel. Call a companion bound to you that stays until dismissed, reserving 50 eitr. Its first element rune picks its form, and every element rune adds stats and abilities (rule "Pet packages"): it can tank, heal, support or deal damage. If it dies, the reservation lifts but that eitr comes back empty; call it again once you have 50 eitr.

### Support Totem

*Common | Steel | Ground-target totem | 25 eitr | 60s cooldown*

Plant a support totem (100 HP) for 300s; planting is an 8s channel. Every 3s it pulses in 7m: allies inside gain half of the element's Buff effect, which lasts 8s after each pulse (Steel, the default: +11 armor, half of Steel's buff; Earth: can't be Staggered at half strength; Lightning +5% attack speed; and so on).

### Trapper's Cache

*Common | Steel | Placed trap | 20 stamina | 15s cooldown*

1s channel. Set one concealed trap (lasts 60s). It arms in about 3s; the first enemy to trigger it takes 150 element damage, is Staggered and gains the element's status.

### War Totem

*Common | Frost | Ground-target totem | 25 eitr | 60s cooldown*

Plant a war totem (100 HP) for 300s; planting is an 8s channel. Every 3s it fires a bolt at one enemy within 15m for 5 element damage, applying the element's status.

## Support

### Boon

*Common | Lightning | Ally (20m) or self | 20 eitr | 10s cooldown*

Bless one ally (or yourself) for 3 minutes. The element decides what it boosts (its Buff effect, for example Lightning +10% attack speed or Steel +15 armor). Milder than a shout, but it lasts. Casting it again refreshes it.

### Lay of Mending

*Uncommon | Holy | Song (20m, lasts 3 min) | 30 eitr | 5s cooldown*

Health song (30 eitr, lasts 3 minutes on everyone it reaches; only one song can affect a player at a time, and the stronger one wins): you and allies within 20m regenerate 1.5 HP per second. Songs only reach allies.

### Leap of the Winds

*Common | Lightning | Self (jump) | 20 stamina | 8s cooldown*

Leap 8m forward in a small arc the way you're moving, or leap 6m straight up if you're standing still, on a gust of storm-wind, with a slow fall (no fall damage). With Lightning (its default) it grows with each extra Lightning rune in its modifier slots: 1, hold jump to glide for up to 6s; 2, glide and dash forward once in mid-air; 3 (every slot Lightning), fly for 6s (jump to rise, sprint to dash). Other elements change how it moves (their Movement effect): Arcane makes it a blink, Shadow puts you behind the target.

### Rise

*Uncommon | Earth | Self or aimed spot (10m) | 20 eitr | 15s cooldown*

Raise a 2m-wide pillar 4m high under your feet (or at the spot you aim at, up to 10m) over 1s; it lasts 20s. Aimed at a gap or cliff, it grows forward as an 8m bridge instead. The element picks the material: Earth (default) stone (sturdier, Staggers enemies it lifts); Steel metal; Frost ice (slick: enemies on or against it are Chilled every 2s, and each second an enemy moves on it, it has a 20% chance to stumble, Staggered; Large creatures 10%, bosses never); Nature vines (climbable); Shadow a dark pillar (you are Stealthed while you stand on it and don't attack); Arcane a rune pillar (enemies touching it are Spellbound); other elements add their status to enemies touching it. Reach makes it taller or longer, Wide makes it a platform, Lingering makes it last. Can't be cast while you stand on a Rise, and obeys no-build zones (boss altars, dungeons). Useful out of combat for climbing and crossing. It never stays: it always crumbles when its time runs out.

### Shout

*Common | Steel | Self AoE (5m) | 25 stamina | 60s cooldown*

Shout: you and allies within 5m gain twice the element's Buff effect for 15s (Steel: +30 armor). Short and strong; Boon is long and mild. Area runes make it reach farther.

### Skald's Refrain

*Uncommon | Holy | Song (20m, lasts 3 min) | 30 eitr | 5s cooldown*

Stamina song (30 eitr, lasts 3 minutes on everyone it reaches; only one song can affect a player at a time, and the stronger one wins): you and allies within 20m gain +25% stamina regen. Songs only reach allies.

### Well-Song of Wisdom

*Uncommon | Arcane | Song (20m, lasts 3 min) | 30 eitr | 5s cooldown*

Eitr song (30 eitr, lasts 3 minutes on everyone it reaches; only one song can affect a player at a time, and the stronger one wins): you and allies within 20m gain +25% eitr regen. Songs only reach allies.

## Tank

### Bear Form

*Rare | Nature | Shapeshift (20s) | 30 stamina | 60s cooldown*

Become a bear for 20s: +40% max health, 20% damage reduction, and swipes that hit a 3m arc for 50 element damage and Taunt. -20% move speed. Other abilities except stances can't be used in form.

### Brace

*Common | Steel | Self | 20 stamina | 30s cooldown*

Plant your feet for 6s: take 30% less damage and cannot be Staggered or knocked back. Movement speed -30% while braced.

### Challenging Roar

*Common | Steel | Target (15m) | 20 stamina | 12s cooldown*

Roar a challenge at one enemy: it is Taunted for 5s and gains the element's status.

### Great-Shield Wall

*Uncommon | Steel | Self (hold block) | 15 stamina | 10s cooldown*

Plant your great shield and hold block: a large glowing shield in front of you blocks attacks from the front for you and allies within 4m behind you. Needs a Warfare great shield.

### Guardian's Stance

*Uncommon | Steel | Self stance (toggle) | 10 stamina | 3s cooldown*

Physical stance (no eitr; only one physical stance at a time): +20% block power and 10% damage reduction; perfect parries deal 30 element damage to the attacker. -10% move speed.

### Retribution Slam

*Rare | Earth | Melee | 35 stamina | 25s cooldown*

Release 25% of the damage you blocked in the last 8s (cap 300) on one enemy in reach, as element damage.

### Riposte

*Uncommon | Steel | Self (parry window) | 15 stamina | 8s cooldown*

Ready a 1s parry window: a parried or blocked hit in that window triggers a counter for 200% weapon damage as element damage and refunds 50% stamina.

### Shield Bash

*Common | Steel | Melee | 15 stamina | 6s cooldown*

Bash with your shield (or forearm) for 100% block power as element damage; Staggers the target and Taunts it for 4s. Requires a shield or Unarmed.

## Signature abilities

There are 35 signature abilities. The first time you beat a boss, you choose its signature ability or its trophy rune; the other is lost for that character. Signatures are your strongest abilities, take no runes and show in gold.


> **More to come: Signature abilities**
> What each one does is a surprise. Choose with care.


---
*Fate Woven is designed by a human, who decides what it does and how it plays. The code is written by Claude, an AI model made by Anthropic, working from that design. The documentation is written by Claude too, and the icons are AI-generated.*
