---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/8
- monster/size/huge
- monster/type/undead
aliases: ["Oblivion Juggernaut"]
---
# Oblivion Juggernaut
*Source: Grim Hollow: Lairs of Etharis p. 28*  

> [!quote]-  
> 
> If you hear the strange, low whistling in the darkness, run! They whistle before they strike, striding out of the darkness, hungry for the souls of the living.

## Salvage

There is a 25% chance that an oblivion stalker leaves behind a gemstone when it is defeated. These stones are worth between 10 and 500 gp, depending on the size of the creature. There is a 10% chance that one of these stones acts as a magnet to additional oblivion stalkers, which appear and attack the holder of the gem at midnight during a new moon. A remove curse makes the gemstone safe.

## Lore

- **DC 10 Intelligence ([History](/Systems/5e/rules/skills.md#History)).** An oblivion stalker is at disadvantage in daylight.  
- **DC 15 Intelligence ([Arcana](/Systems/5e/rules/skills.md#Arcana)).** An oblivion stalker is vulnerable to radiant damage and resistant to nonmagical weapons.  
- **DC 20 Intelligence ([Religion](/Systems/5e/rules/skills.md#Religion)).** If an oblivion stalker kills a mortal, it's believed that mortal joins their shadowy ranks.  

> [!note] Customizing Oblivion Stalkers
> 
> Since oblivion stalkers can drain almost any living creature's energy, they can take just about any form. Some oblivion stalkers retain the natural abilities of their original form. For instance, an oblivion stalker that was once a wolf might retain the Pack Tactics trait. Similarly, a boar could possess a version of Charge, draining its prey while adding slashing damage and the possibility of knocking their victim prone.
> 
> Keep one special ability that makes sense for a creature of the stalker's former form without affecting the Challenge of the stalker. Avoid bestowing an oblivion stalker any ability that is magical, grants the stalker a ranged attack, or expands its resistances or immunities.
^customizing-oblivion-stalkers

## Statblock

```ad-statblock
title: Oblivion Juggernaut
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GHLoE/Oblivion%20Juggernaut.webp#token)
*Huge undead, Neutral Evil*

- **Armor Class** 12
- **Hit Points** 85 (`10d12 + 20`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|15 (+2)|10 (+0)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** radiant
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [frightened](/Systems/5e/rules/conditions.md#frightened), [grappled](/Systems/5e/rules/conditions.md#grappled), [paralyzed](/Systems/5e/rules/conditions.md#paralyzed), [petrified](/Systems/5e/rules/conditions.md#petrified), [poisoned](/Systems/5e/rules/conditions.md#poisoned), [prone](/Systems/5e/rules/conditions.md#prone), [restrained](/Systems/5e/rules/conditions.md#restrained)
- **Languages** —
- **Challenge** 8

## Traits

***Shadow Stealth.*** While in dim light or darkness, the oblivion juggernaut can take the Hide action as a bonus action.

***Sunlight Weakness.*** While in sunlight, the oblivion juggernaut has disadvantage on attack rolls, ability checks, and saving throws.

## Actions

***Multiattack.*** The oblivion juggernaut uses unbearable roar and then uses soul drain.

***Soul Drain.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one creature. *Hit:* 26 (`4d10 + 4`) necrotic damage, and the target must make a DC 13 Constitution saving throw. On a failure, the target's available Hit Dice are reduced by 2. If this effect reduces the target's Hit Dice to 0, the target falls [unconscious](/Systems/5e/rules/conditions.md#unconscious). The target can repeat the saving throw at the end of each of its turns, regaining consciousness on a success. Hit Dice lost this way return at the end of a short rest, in time to spend them to regain hit points.

If an oblivion juggernaut kills a living creature with this attack when the creature is at 0 Hit Dice, the target's soul is lost to the realm of shadow. This lost soul can be raised from the dead only with mighty magic, such as wish or divine intervention.

***Unbearable Roar.*** Each creature of the oblivion juggernaut's choice that isn't [deafened](/Systems/5e/rules/conditions.md#deafened) and is within 120 feet of the juggernaut must succeed on a DC 18 Wisdom saving throw or become [frightened](/Systems/5e/rules/conditions.md#frightened) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to any oblivion juggernaut's Unbearable Roar for 24 hours.
```
^statblock