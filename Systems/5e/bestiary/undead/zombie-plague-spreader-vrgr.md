---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Zombie Plague Spreader"]
---
# Zombie Plague Spreader
*Source: Van Richten's Guide to Ravenloft p. 255*  

Among the undead, a lone zombie ranks far from the most menacing. The horror of the shambling dead lies not in their individual menace, though, but their numbers, their persistence, and their disregard for their own well-being. A throng of zombies will douse a forest fire with their own ashes or march into a dragon's maw until the monster chokes. In the course of their relentless marches, zombies might suffer all manner of trauma, potentially reducing them to masses of crawling limbs (see swarm of zombie limbs), infecting them with terrible diseases, or crushing an entire horde into a single, rotting titan (see zombie clot).

## Zombie Apocalypses

Among the types of horror adventures detailed in "chapter 2", tales of uncontrolled zombie outbreaks orbit the "dark fantasy" and "disaster horror" genres. The horror of these adventures focuses not on the terror of a single zombie, but of countless individual threats overwhelming society. When creating your own undead calamities, consider the plots presented on the Zombie Apocalypses table.

**Zombie Apocalypses**

`dice: [](zombie-plague-spreader-vrgr.md#^zombie-apocalypses)`

| dice: d4 | Zombie Plot |
|----------|-------------|
| 1 | A twisted wish causes those affected by healing magic and [potions of healing](/Systems/5e/items/potion-of-healing.md) to rise as zombies. |
| 2 | Overwhelming magic reanimates zombies again and again as [swarms of zombie limbs](/Systems/5e/bestiary/undead/swarm-of-zombie-limbs-vrgr.md). |
| 3 | The githyanki unleash [zombie plague spreaders](/Systems/5e/bestiary/undead/zombie-plague-spreader-vrgr.md) to scour mind flayers from a world. |
| 4 | The seals containing an underground zombie horde fail, releasing ancient [zombie clots](/Systems/5e/bestiary/undead/zombie-clot-vrgr.md). |
^zombie-apocalypses

## Statblock

```ad-statblock
title: Zombie Plague Spreader
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/VRGR/Zombie%20Plague%20Spreader.webp#token)
*Medium undead, Unaligned*

- **Armor Class** 10
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|15 (+2)| 3 (-4)| 5 (-3)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 7
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](/Systems/5e/rules/conditions.md#charmed), [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 4

## Traits

***Undead Fortitude.*** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

***Unusual Nature.*** The zombie doesn't require air, food, drink, or sleep.

***Viral Aura.*** Any creature that starts its turn within 10 feet of the plague spreader must make a DC 12 Constitution saving throw. On a failed save, the creature is [poisoned](/Systems/5e/rules/conditions.md#poisoned) and can't regain hit points until the end of its next turn. On a successful save, the creature is immune to this plague spreader's Viral Aura for 24 hours.

## Actions

***Multiattack.*** The plague spreader makes two Slam attacks.

***Slam.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) bludgeoning damage plus 9 (`2d8`) necrotic damage.

***Virulent Miasma (1/Day).*** The plague spreader releases toxic gas in a 30-foot-radius sphere centered on itself. Each creature in that area must make a DC 12 Constitution saving throw, taking 14 (`4d6`) poison damage on a failed save, or half as much damage on a successful one. A Humanoid reduced to 0 hit points by this damage dies and rises as a zombie (see its stat block in the Monster Manual) 1 minute later. The zombie acts immediately after the plague spreader in the initiative count.
```
^statblock