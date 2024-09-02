---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/4
- monster/size/small-or-medium
- monster/type/humanoid/druid
aliases: ["Witherbloom Pledgemage"]
---
# Witherbloom Pledgemage
*Source: Strixhaven: A Curriculum of Chaos p. 222*  

Deep in the fog and muck of the swamp, the students of Witherbloom College—first as apprentices and then as pledgemages—study the cycle of life and death. Their magic is fueled by what they call life essence: the ubiquitous energy that runs through living things.

Witherbloom students learn how to concoct magical potions and talismans, in addition to their spellcasting studies. Their magic ranges from necrotic shadows and withering bursts of poison to flourishing bursts of plant life.

## Witherbloom Scholars

Witherbloom College studies the magic inherent in the natural cycle of life and death. Witherbloom professors approach the philosophy from different directions, with one methodology focusing on decay and the other dealing with growth.

## Statblock

```ad-statblock
title: Witherbloom Pledgemage
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/SCC/Witherbloom%20Pledgemage.webp#token)
*Small or Medium humanoid (druid), Any alignment*

- **Armor Class** 12 (15 with vociferous form)
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|13 (+1)|14 (+2)|17 (+3)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +3, Wisdom +5
- **Skills** Medicine +5, Nature +6, Perception +7
- **Senses** passive Perception 17
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** Common plus any two languages
- **Challenge** 4

## Traits

***Regeneration.*** As long as the pledgemage has at least 1 hit point remaining, the pledgemage regains 5 hit points at the start of its turn.

***Verdant Talisman.*** At the end of a 10-minute ritual, the pledgemage can touch one willing creature (including itself) and bestow upon it a small talisman imbued with magic. Upon receiving the talisman, the creature gains 10 temporary hit points, and it can add `1d6` to its initiative rolls while it wears the talisman. These benefits last for 1 hour or until the pledgemage conducts another ritual to bestow another talisman. When the benefits expire, the talisman crumbles to dust.

***Spellcasting.*** The apprentice casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability:

**At will**: [druidcraft](/Systems/5e/spells/druidcraft.md), [spare the dying](/Systems/5e/spells/spare-the-dying.md)

**1/day each**: [death ward](/Systems/5e/spells/death-ward.md), [pass without trace](/Systems/5e/spells/pass-without-trace.md), [speak with plants](/Systems/5e/spells/speak-with-plants.md)

## Actions

***Briar Vine.*** *Melee Spell Attack:* `+5` to hit, reach 15 ft., one target. *Hit:* 8 (`1d10 + 3`) piercing damage plus 18 (`4d8`) poison damage. If the target is a Large or smaller creature, the apprentice can pull it up to 10 feet closer to itself.

## Bonus Actions

***Vociferous Form (1/Day).*** The pledgemage transforms into an avatar of plants and shadow. While in this form, the pledgemage adds its Wisdom modifier to its AC if it isn't wearing armor or wielding a shield, and it has advantage on attack rolls against any creature missing hit points. This form lasts for 1 minute or until the pledgemage is reduced to 0 hit points.

## Reactions

***Wither Burst.*** When the pledgemage sees a creature within 30 feet of itself drop to 0 hit points, the pledgemage channels the expended life essence and targets another creature it can see within 30 feet of itself. The target must succeed on a DC 13 Constitution saving throw or become [poisoned](/Systems/5e/rules/conditions.md#poisoned) for 1 minute. While [poisoned](/Systems/5e/rules/conditions.md#poisoned) in this way, the target takes 3 (`1d6`) poison damage at the start of each of its turns. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success.
```
^statblock