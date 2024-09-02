---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/3
- monster/size/medium
- monster/type/aberration
aliases: ["Flying Horror"]
---
# Flying Horror
*Source: Guildmasters' Guide to Ravnica p. 203*  

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

`dice: [](flying-horror-ggr.md#^primary-features)`

| dice: d4 | Feature |
|----------|---------|
| 1 | Avoidance. If the horror is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. |
| 2 | Damage Resistances. The horror has resistance to necrotic and psychic damage. |
| 3 | Innate Spellcasting. The horror's innate spellcasting ability is Charisma (spell save DC 13 for flying horror, DC 16 for shadow horror, and DC 17 for skittering horror). It can innately cast the following spells, requiring no material components: 3/day: [darkness](/Systems/5e/spells/darkness.md) 1/day each: [fear](/Systems/5e/spells/fear.md) (shadow horror and skittering horror only), [phantasmal killer](/Systems/5e/spells/phantasmal-killer.md) (skittering horror only) |
| 4 | Psychic Rebuke. When the horror takes damage from a melee attack, it can use its reaction to emit psychic energy within a 5-foot radius. Each creature in that area takes 3 (`1d6`) psychic damage (flying horror), 7 (`2d6`) psychic damage (shadow horror), or 10 (`3d6`) psychic damage (skittering horror). |
^primary-features

**Secondary Features**

`dice: [](flying-horror-ggr.md#^secondary-features)`

| dice: d4 | Feature |
|----------|---------|
| 1 | Grasping Tendrils. The horror has four tendrils. Each tendril can be attacked (AC 12, 10 hit points). Destroying one deals no damage to the horror. As a bonus action, the horror can target one creature it can see within 10 feet of it. The target must succeed on a Dexterity saving throw or be [grappled](/Systems/5e/rules/conditions.md#grappled) by the horror. The DC of the saving throw and the DC to escape the grapple are the same: 9 for the flying horror, 13 for the shadow horror, and 19 for the skittering horror. Until the grapple ends, the horror can't use the same tendril to grapple another target. |
| 2 | Indomitable Mind. The horror is immune to the [charmed](/Systems/5e/rules/conditions.md#charmed) condition. |
| 3 | Keen Senses. The horror has advantage on Wisdom ([Perception](/Systems/5e/rules/skills.md#Perception)) checks that rely on sight, sound, or smell. |
| 4 | Mind Sight. Magical darkness doesn't impede the horror's [darkvision](/Systems/5e/rules/senses.md#darkvision). |
^secondary-features

## Statblock

```ad-statblock
title: Flying Horror
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GGR/Flying%20Horror.webp#token)
*Medium aberration, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 49 (`9d8 + 9`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|20 (+5)|12 (+1)| 2 (-4)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +7
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Vulnerabilities** radiant
- **Condition Immunities** [frightened](/Systems/5e/rules/conditions.md#frightened)
- **Languages** —
- **Challenge** 3

## Traits

***Fear Frenzy.*** The horror has advantage on attack rolls against [frightened](/Systems/5e/rules/conditions.md#frightened) creatures.

***Sunlight Sensitivity.*** While in sunlight, the horror has disadvantage on attack rolls and on Wisdom ([Perception](/Systems/5e/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Claws.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 8 (`1d6 + 5`) slashing damage plus 14 (`4d6`) psychic damage.

***Frightening Screech (Recharge 5-6).*** The horror screeches. Each creature within 30 feet of it that can hear it must succeed on a DC 13 Wisdom saving throw or be [frightened](/Systems/5e/rules/conditions.md#frightened) of it for 1 minute. The [frightened](/Systems/5e/rules/conditions.md#frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the horror's Frightening Screech for the next 24 hours.
```
^statblock