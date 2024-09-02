---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Eldritch Herald"]
---
# Eldritch Herald
*Source: Grim Hollow: Lairs of Etharis p. 41*  

> [!quote]-  
> 
> First she spoke of a power greater than the gods. Then there was this ringing in my ears. I don't remember what happened after that, but the nightmares were terrible.

## Salvage

The touch of an Aether Kindred's dreams can taint objects with an unstable nature, particularly potions. Any potion found on the servants of these beings has a 50 percent chance to be tainted, making the potion's effects unpredictable. Someone inspecting such a potion must succeed on a DC 17 Intelligence ([Arcana](/Systems/5e/rules/skills.md#Arcana)) check to identify the instability. Otherwise, the potion appears to be a normal potion of its type.

When an unstable potion is consumed, roll on the Eldritch Effects table to determine the effect of the instability, which is in addition to the potion's normal effects and can last as long as the potion does or 1 minute, whichever is longer. However, a creature can attempt a DC 13 Wisdom saving throw at the end of each of its turns, ending the instability effect on itself on a success.

## Lore

- **DC 10 Intelligence ([History](/Systems/5e/rules/skills.md#History)).** In the wake of the gods' disappearance, some turned to other ancient entities for power. Those that succeed are known as eldritch priests.  
- **DC 15 Intelligence ([Arcana](/Systems/5e/rules/skills.md#Arcana)).** These priests draw their power from maddening entities known as the Aether Kindred, which some arcane scholars point to as the cause of the gods' disappearance. The power granted by such creatures can produce bizarre and unpredictable effects.  
- **DC 20 Intelligence ([Religion](/Systems/5e/rules/skills.md#Religion)).** Some eldritch priests seek to awaken their new "gods" by spreading the story of the demise of members the Etharis pantheon. As more people tap into the dreams of the slumbering Kindred, the creatures begin to rouse. If they wake, the world is doomed.  

## Eldritch Effects

`dice: [](eldritch-herald-ghloe.md#^effect)`

| dice: d8 | Effect |
|----------|--------|
| 1 | The creature can't speak. |
| 2 | The creature takes 4 (`1d8`) psychic damage at the start of each of its turns. |
| 3 | The creature is disoriented. It falls prone and does so again at the end of each turn it moves 5 feet or more. |
| 4 | The creature is distracted by visions and voices and has disadvantage on attack rolls and Wisdom ([Perception](/Systems/5e/rules/skills.md#Perception)) checks. |
| 5 | The creature is unsure of itself. It can move or take an action on its turn, but not both, and it can't use reactions. |
| 6 | The creature is reckless. It has advantage on attack rolls and attack rolls against it have advantage. |
| 7 | The creature is deafened and can't see more than 30 feet away. |
| 8 | The creature is frightened of the source of this effect. If that source can't be sensed, the creature is frightened of one other random creature it can sense. |
^effect

## Statblock

```ad-statblock
title: Eldritch Herald
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GHLoE/Eldritch%20Herald.webp#token)
*Medium humanoid (any race), Any Non-Good alignment*

- **Armor Class** 16 ([breastplate](/Systems/5e/items/breastplate.md), [shield](/Systems/5e/items/shield.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|11 (+0)|15 (+2)|10 (+0)|17 (+3)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6, Religion +3
- **Senses** passive Perception 16
- **Damage Resistances** psychic
- **Languages** any two languages
- **Challenge** 5

## Traits

***Otherworldly Calm.*** The eldritch herald has advantage on saving throws against being [charmed](/Systems/5e/rules/conditions.md#charmed) or [frightened](/Systems/5e/rules/conditions.md#frightened). Also, attempts to read the herald's thoughts fail. The creature making the attempt must succeed on a DC 14 Wisdom saving throw or take 10 (`3d6`) psychic damage.

***Spellcasting.*** The herald is a 12th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 14, `+6` to hit with spell attacks). It has the following cleric spells prepared:

**Cantrips (at will)**: [light](/Systems/5e/spells/light.md), [sacred flame](/Systems/5e/spells/sacred-flame.md), [thaumaturgy](/Systems/5e/spells/thaumaturgy.md), [vicious mockery](/Systems/5e/spells/vicious-mockery.md)

**1st level (4 slots)**: [bane](/Systems/5e/spells/bane.md), [Tasha's hideous laughter](/Systems/5e/spells/tashas-hideous-laughter.md), [inflict wounds](/Systems/5e/spells/inflict-wounds.md), [sleep](/Systems/5e/spells/sleep.md)

**2nd level (3 slots)**: [detect thoughts](/Systems/5e/spells/detect-thoughts.md), [hold person](/Systems/5e/spells/hold-person.md), [see invisibility](/Systems/5e/spells/see-invisibility.md), [wrack](/Systems/5e/spells/wrack-ghloe.md) *

**3rd level (3 slots)**: [bestow curse](/Systems/5e/spells/bestow-curse.md), [fear](/Systems/5e/spells/fear.md), [spirit guardians](/Systems/5e/spells/spirit-guardians.md), [tongues](/Systems/5e/spells/tongues.md)

**4th level (3 slots)**: [confusion](/Systems/5e/spells/confusion.md), [death ward](/Systems/5e/spells/death-ward.md), [phantasmal killer](/Systems/5e/spells/phantasmal-killer.md)

**5th level (2 slots)**: [contact other plane](/Systems/5e/spells/contact-other-plane.md), [contagion](/Systems/5e/spells/contagion.md), [dream](/Systems/5e/spells/dream.md)

**6th level (1 slots)**: [true seeing](/Systems/5e/spells/true-seeing.md)

## Actions

***Handaxe.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 5 (`1d6 + 2`) slashing damage.

***Prophecy of Doom (Recharges after a Short or Long Rest).*** The eldritch herald chooses a point it can see within 120 feet of it and rolls on the Eldritch Effects table. Each creature within 15 feet of that point must succeed on a DC 14 Wisdom saving throw or be subjected to an eldritch effect for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock