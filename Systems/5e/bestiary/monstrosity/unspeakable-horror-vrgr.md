---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["Unspeakable Horror"]
---
# Unspeakable Horror
*Source: Van Richten's Guide to Ravenloft p. 250*  

Untold, half-formed evils lurk amid the Mists, the yet-to-be-realized imaginings of the Dark Powers and the remnants of ruined domains. While such nightmares typically manifest as nothing more than impressions, whispers, or vaporous visions amid the fog, mysterious eddies in the Mists sometimes gather such evils, forcing them into unique, misshapen bodies untethered from the laws of reason or reality. Such unspeakable horrors might continue to haunt the misty netherworld between the Domains of Dread, or they might slink forth into other realms to slake unnameable hungers.

## Customizing a Horror

An unspeakable horror has one of four body compositions, determined by rolling on the Body Composition table. You can roll on the Limbs to customize it further, while results from the Hex Blast table replace that action in the stat block. If the results of multiple tables conflict, chose your preferred result.

The results of these tables are meant to be broad, so feel free to describe the details of an unspeakable horror's form and the interplay between its parts however you desire. The more discordant and unexpected a horror's parts, the more unsettling it might be.

## Mist Horrors

Some who wander into the Land of the Mists seek to stay hidden in the haze. They might even wish to dwell amid the endless fog, finding it preferable to horrors elsewhere. But the Mists drifting between the Domains of Dread are far from safe—or empty.

Mist horrors are bodiless spirits of dread, entities given form by the fears of those they encounter. Mist horrors use the unspeakable horror stat block with the Malleable Mass body option, which makes them appear to be composed of living mist. Further details of a mist horror's appearance are drawn from the fears of those within 100 feet of it. This might cause a mist horror to take on a form that combines multiple fears when it encounters a group, like a wolf with snakes for eyes or a drowned giant that resembles an estranged parent. Mist horrors can't persist for long outside the Mists: after `1d4` rounds outside the Mists, they lose cohesion and collapse back into harmless vapor.

**Body Composition**

`dice: [](unspeakable-horror-vrgr.md#^body-composition)`

| dice: d4 | Body |
|----------|------|
| 1 | **Aberrant Armor.** The horror's body is armored in petrified wood, alien crystal, rusted mechanisms, sculpted stone, or an exoskeleton. |
| 2 | **Loathsome Limbs.** The horror's body boasts spider like legs, many-jointed appendages, or thrashing tentacles. |
| 3 | **Malleable Mass.** The horror's body is composed of a clot of boneless flesh, shadowy tendrils, or mist. |
| 4 | **Oozing Organs.** The horror's body boasts exposed entrails, bloated parasites, or a gelatinous shroud, perhaps because it is inside out. |
^body-composition

**Hex Blast**

`dice: [](unspeakable-horror-vrgr.md#^hex-blast)`

| dice: d4 | Hex |
|----------|-----|
| 1 | **Beguiling Hex (Recharge 5-6).** The horror expels a wave of mind-altering magic. Each creature within 30 feet of the horror must make a DC 15 Wisdom saving throw, taking 33 (`6d10`) psychic damage and being incapacitated until the end of the creature's next turn on a failed save, or taking half as much damage on a successful one. |
| 2 | **Bile Hex (Recharge 5-6).** The horror expels acidic bile in a 60-foot line that is 5 feet wide. Each creature in that line must succeed on a DC 15 Dexterity saving throw or be covered in bile. A creature covered in bile takes 31 (`7d8`) acid damage at the start of each of its turns until it or another creature uses its action to scrape or wash off the bile that covers it. |
| 3 | **Petrifying Hex (Recharge 5-6).** The horror expels petrifying gas in a 30-foot cone. Each creature in that area must succeed on a DC 15 Constitution saving throw or take 14 (`4d6`) necrotic damage and be restrained as it begins to turn to stone. A restrained creature must repeat the saving throw at the end of its next turn. On a success, the effect ends on the target. On a failure, the target is petrified until freed by the [greater restoration](/Systems/5e/spells/greater-restoration.md) spell or other magic. |
| 4 | **Reality-Stealing Hex (Recharge 5-6).** The horror expels a wave of perception-distorting energy. Each creature within 30 feet of the horror must make a DC 15 Wisdom saving throw. On a failed save, the target takes 22 (`5d8`) psychic damage and is deafened until the end of its next turn. If the saving throw fails by 5 or more, the target is also blinded until the end of its next turn. |
^hex-blast

**Limbs**

`dice: [](unspeakable-horror-vrgr.md#^limbs)`

| dice: d4 | Attack |
|----------|--------|
| 1 | **Bone Blade.** The horror's limb ends in a blade made of bone, which deals slashing damage instead of bludgeoning damage. In addition, it scores a critical hit on a roll of 19 or 20 and rolls the damage dice of a crit three times, instead of twice. |
| 2 | **Corrosive Pseudopod.** The horror's limb attack deals an extra 9 (`2d8`) acid damage. |
| 3 | **Grasping Tentacle.** The horror's limb is a grasping tentacle. When the horror hits a creature with this limb, the creature is also grappled (escape DC 16). The limb can have only one creature grappled at a time. |
| 4 | **Poisonous Limb.** The horror's limb deals piercing damage instead of bludgeoning damage. In addition, when the horror hits a creature with this limb, the creature must succeed on a DC 15 Constitution saving throw or take 7 (`2d6`) poison damage and be poisoned until the end of its next turn. |
^limbs

## Statblock

```ad-statblock
title: Unspeakable Horror
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/VRGR/Unspeakable%20Horror.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 (natural armor; 17 from Aberrant Armor Only)
- **Hit Points** 95 (`10d10 + 40`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|13 (+1)|19 (+4)| 3 (-4)|14 (+2)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7, Wisdom +5
- **Skills** Perception +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Languages** —
- **Challenge** 8

## Traits

***Formed by the Mists.*** When created, the horror's body composition takes one of four forms: Aberrant Armor, Loathsome Limbs, Malleable Mass, or Oozing Organs. This form determines certain traits in this stat block.

***Amorphous (Malleable Mass Only).*** The horror can move through any opening at least 1 inch wide without squeezing.

***Bile Body (Oozing Organs Only).*** Any creature that touches the horror or hits it with a melee attack takes 5 (`1d10`) acid damage.

***Relentless Stride (Loathsome Limbs Only).*** The horror can move through the space of another creature. The first time on a turn that the horror enters a creature's space during this move, the creature must succeed on a DC 16 Strength saving throw or be knocked [prone](/Systems/5e/rules/conditions.md#prone).

## Actions

***Multiattack.*** The horror makes two Limbs attacks.

***Limbs.*** *Melee Weapon Attack:* `+8` to hit, reach 5 ft., one target. *Hit:* 21 (`3d10 + 5`) bludgeoning damage.

***Hex Blast (Recharge 5-6).*** The horror expels necrotic energy in a 30-foot cone. Each creature in that area must make a DC 15 Constitution saving throw, taking 45 (`7d12`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock