---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/medium
- monster/type/construct
aliases: ["Clockwork Stone Defender"]
---
# Clockwork Stone Defender
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 80, Mordenkainen's Tome of Foes p. 126, Return to Glory p. 35*  

The thick plates of stone riveted onto a stone [defender](/Systems/5e/items/defender.md) give it substantial protection. Its chief role is as a bodyguard.

## Clockworks

Gnomes' tinkering with magic and mechanical devices has produced many failed Constructs but also has resulted in genuine advances, such as clockworks. The methods used to craft clockworks have been shared between gnome communities over many generations.

### Individual Designs

Gnome artisans prefer unique clockworks over perfectly functioning ones that copy too much from other creations. A clockwork can be customized by adding one of the following enhancements and one potential malfunction to its stat block. You can select randomly or choose a pair of modifications that fit the temperament of the clockwork's builder.

**Clockwork Enhancements**

`dice: [](clockwork-stone-defender-mpmm.md#^clockwork-enhancements)`

| dice: d10 | Enhancement |
|-----------|-------------|
| 1 | **Camouflaged.** The clockwork gains proficiency in [Stealth](/Systems/5e/rules/skills.md#Stealth) if it lacks that proficiency. While motionless, it is indistinguishable from a stopped machine. |
| 2 | **Sensors.** The range of the clockwork's [darkvision](/Systems/5e/rules/senses.md#darkvision) increases by 60 feet, and it gains proficiency in [Perception](/Systems/5e/rules/skills.md#Perception) if it lacks that proficiency. |
| 3 | **Fortified.** The clockwork's AC increases by 2. |
| 4 | **Increased Speed.** The clockwork's speed increases by 10 feet. |
| 5 | **Reinforced Construction.** The clockwork has resistance to force, lightning, and thunder damage. |
| 6 | **Self-Repairing.** If the clockwork starts its turn with fewer than half its hit points but at least 1 hit point, it regains 5 hit points. If it takes lightning damage, this ability doesn't function at the start of its next turn. |
| 7 | **Sturdy Frame.** The clockwork's hit point maximum increases by an amount equal to its number of Hit Dice. |
| 8 | **Suction.** The clockwork gains a climbing speed of 30 feet. |
| 9 | **Vocal Resonator.** The clockwork gains the ability to speak rudimentary Common or Gnomish. |
| 10 | **Water Propulsion.** The clockwork gains a swimming speed of 30 feet. |
^clockwork-enhancements

**Clockwork Malfunctions**

`dice: [](clockwork-stone-defender-mpmm.md#^clockwork-malfunctions)`

| dice: d8 | Malfunction |
|----------|-------------|
| 1 | **Faulty Sensors.** Roll a `d6` at the start of the clock work's turn. If you roll a 1, the clockwork is [blinded](/Systems/5e/rules/conditions.md#blinded) until the end of its turn. |
| 2 | **Flawed Targeting.** Roll a `d6` at the start of the clock work's turn. If you roll a 1, the clockwork makes attack rolls with disadvantage until the end of its turn. |
| 3 | **Ground Fault.** The clockwork has vulnerability to lightning damage. |
| 4 | **Imprinting Loop.** Roll a `d6` at the start of the clock work's turn. If you roll a 1, the clockwork mistakes one creature it can see within 30 feet for its creator. The clockwork won't willingly harm that creature for 1 minute or until that creature attacks or dam ages it. |
| 5 | **Limited Steering.** The clockwork must move in a straight line. It can turn up to 90 degrees before moving and again at the midpoint of its movement. It can rotate freely if it doesn't use any of its speeds on its turn. |
| 6 | **Overactive Sense of Self-Preservation.** If the clock work has half its hit points or fewer at the start of its turn in combat, roll a `d6`. If you roll a 1, it retreats from combat if possible. It otherwise keeps fighting. |
| 7 | **Overheats.** Roll a `d6` at the start of the clockwork's turn. If you roll a 1, the clockwork is [incapacitated](/Systems/5e/rules/conditions.md#incapacitated) until the end of its turn. |
| 8 | **Rusty Gears.** The clockwork has disadvantage on initiative rolls, and its speed decreases by 10 feet. |
^clockwork-malfunctions

## Statblock

```ad-statblock
title: Clockwork Stone Defender
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPMM/Clockwork%20Stone%20Defender.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|10 (+0)|17 (+3)| 3 (-4)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](/Systems/5e/rules/conditions.md#charmed), [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [frightened](/Systems/5e/rules/conditions.md#frightened), [paralyzed](/Systems/5e/rules/conditions.md#paralyzed), [petrified](/Systems/5e/rules/conditions.md#petrified), [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** understands one language of its creator but can't speak
- **Challenge** 4

## Traits

***Magic Resistance.*** The clockwork has advantage on saving throws against spells and other magical effects.

***Unusual Nature.*** The clockwork doesn't require air, food, drink, or sleep.

## Actions

***Slam.*** *Melee Weapon Attack:* `+6` to hit, reach 5 ft., one target. *Hit:* 11 (`2d6 + 4`) bludgeoning damage, and if the target is Large or smaller, it is knocked [prone](/Systems/5e/rules/conditions.md#prone).

## Reactions

***Intercept Attack.*** In response to another creature within 5 feet of it being hit by an attack roll, the clockwork gives that creature a +5 bonus to its AC against that attack, potentially causing a miss. To use this ability, the clockwork must be able to see the creature and the attacker.
```
^statblock

## Environment

forest, grassland, hill, mountain