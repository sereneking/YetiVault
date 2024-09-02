---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/9
- monster/size/large
- monster/type/aberration
aliases: ["Shadow Horror"]
---
# Shadow Horror
*Source: Guildmasters' Guide to Ravnica p. 205*  

## Horrors and Madness

Horrors on Ravnica are terror and madness personified. You can represent this reality by using the madness rules in the Dungeon Master's Guide.

Whenever a character fails a saving throw against the flying horror's Frightening Screech, the shadow horror's claw attack, or the skittering horror's Maddening Presence, note that fact. At the end of the encounter, have each character who failed at least one of those saving throws make a DC 13 Wisdom saving throw. On a successful save, nothing happens. On a failed save, a character gains a form of madness from the Dungeon Master's Guide, with the severity depending on how many of the saving throws that character failed during the encounter, as shown on the Madness Severity table.

**Madness Severity**

| Failed Saves | Madness |
|--------------|---------|
| 1 | Short-term |
| 2-3 | Long-term |
| 4+ | Indefinite |
^madness-severity

## Horrors

Terrifying evils stalk, fly, and scuttle in the dark corners of Ravnica, from the depths of the undercity to the blackest parts of the night sky. Collectively, these creatures are called horrors-a variety of things that lurk in the dark and embody the deepest fears of Ravnica's people. All are evil creatures with dim reason and preternatural cunning.

At least three guilds have been known to compel horrors into service. For House Dimir, horrors spread fear and despair in the citizenry and carry out assassinations or kidnappings against well-protected targets. For the Cult of Rakdos, horrors are simply one more weapon in an arsenal of terrifying and shock-inspiring creatures that might appear on stage. For the Golgari Swarm, horrors scavenge the sewers and protect the guild's territory.

House Dimir uses all three base kinds of horrors. The Cult of Rakdos prefers shadow horrors, and the Golgari Swarm uses skittering horrors.

## Customizing a Horror

Horrors share some common body types but vary wildly in other characteristics. A particular horror's form might incorporate elements that resemble fiendish, insectile, or reptilian features. To customize a horror, choose a base creature (flying horror, shadow horror, or skittering horror), then roll once on the Primary Features table and once on the Secondary Features table (or choose an option from each table). Add those features to the base creature.

**Primary Features**

`dice: [](shadow-horror-ggr.md#^primary-features)`

| dice: d4 | Feature |
|----------|---------|
| 1 | Avoidance. If the horror is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. |
| 2 | Damage Resistances. The horror has resistance to necrotic and psychic damage. |
| 3 | Innate Spellcasting. The horror's innate spellcasting ability is Charisma (spell save DC 13 for flying horror, DC 16 for shadow horror, and DC 17 for skittering horror). It can innately cast the following spells, requiring no material components: 3/day: [darkness](/Systems/5e/spells/darkness.md) 1/day each: [fear](/Systems/5e/spells/fear.md) (shadow horror and skittering horror only), [phantasmal killer](/Systems/5e/spells/phantasmal-killer.md) (skittering horror only) |
| 4 | Psychic Rebuke. When the horror takes damage from a melee attack, it can use its reaction to emit psychic energy within a 5-foot radius. Each creature in that area takes 3 (`1d6`) psychic damage (flying horror), 7 (`2d6`) psychic damage (shadow horror), or 10 (`3d6`) psychic damage (skittering horror). |
^primary-features

**Secondary Features**

`dice: [](shadow-horror-ggr.md#^secondary-features)`

| dice: d4 | Feature |
|----------|---------|
| 1 | Grasping Tendrils. The horror has four tendrils. Each tendril can be attacked (AC 12, 10 hit points). Destroying one deals no damage to the horror. As a bonus action, the horror can target one creature it can see within 10 feet of it. The target must succeed on a Dexterity saving throw or be [grappled](/Systems/5e/rules/conditions.md#grappled) by the horror. The DC of the saving throw and the DC to escape the grapple are the same: 9 for the flying horror, 13 for the shadow horror, and 19 for the skittering horror. Until the grapple ends, the horror can't use the same tendril to grapple another target. |
| 2 | Indomitable Mind. The horror is immune to the [charmed](/Systems/5e/rules/conditions.md#charmed) condition. |
| 3 | Keen Senses. The horror has advantage on Wisdom ([Perception](/Systems/5e/rules/skills.md#Perception)) checks that rely on sight, sound, or smell. |
| 4 | Mind Sight. Magical darkness doesn't impede the horror's [darkvision](/Systems/5e/rules/senses.md#darkvision). |
^secondary-features

## Statblock

```ad-statblock
title: Shadow Horror
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GGR/Shadow%20Horror.webp#token)
*Large aberration, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 120 (`16d10 + 32`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|14 (+2)| 2 (-4)|17 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +7, Stealth +11
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Vulnerabilities** radiant
- **Condition Immunities** [frightened](/Systems/5e/rules/conditions.md#frightened)
- **Languages** —
- **Challenge** 9

## Traits

***Incorporeal Movement.*** The horror can move through other creatures and objects as if they were difficult terrain. It takes 5 (`1d10`) force damage if it ends its turn inside an object.

***Shadow Stealth.*** While in dim light or darkness, the horror can take the Hide action as a bonus action.

***Shadow Stride.*** As a bonus action, the horror can step into a shadow within 5 feet of it and magically appear in an unoccupied space within 5 feet of a second shadow that is up to 60 feet away. Both shadows must be cast by a Small or larger creature or object.

***Sunlight Sensitivity.*** While in sunlight, the horror has disadvantage on attack rolls and on Wisdom ([Perception](/Systems/5e/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The horror makes three attacks: one with its bite and two with its claws.

***Bite.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 21 (`4d8 + 3`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 13 (`3d6 + 3`) slashing damage, and the target must succeed on a DC 16 Wisdom saving throw or be [frightened](/Systems/5e/rules/conditions.md#frightened) of the horror until the end of the target's next turn.

***Lashing Shadows (Recharge 5-6).*** Each creature within 60 feet of the horror, except other horrors, must succeed on a DC 16 Dexterity saving throw or take 27 (`6d8`) necrotic damage.
```
^statblock