---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Darakhul"]
---
# Darakhul
*Source: Tome of Beasts 1 (2023 Edition) p. 202*  

*Intelligence gleams in the eyes of the well-dressed ghoul. It smiles a greeting, barely revealing sharp teeth.*

## Imperial Cunning

In the lightless depths, an empire of devouring ambition grows and plots and dreams. They call themselves the People, but the people of the surface world call them the Lords Subterranean, the Ghoul Imperium, or simply the Empire of the Ghouls. To them, if you are not a member of the People, you are food.

> [!note] Darakhul Fever
> 
> Spread mainly through bite wounds, this disease makes itself known within 24 hours by swiftly debilitating the infected. An infected creature must make a DC 17 Constitution saving throw after every long rest. On a failed save, the victim takes 14 (`4d6`) necrotic damage, and its hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the victim finishes a long rest after the disease is cured. The victim recovers from the disease by making two consecutive successful saving throws. Greater restoration cures the disease, while lesser restoration gives the victim advantage on the next saving throw. Primarily spread among Humanoids, the disease can affect ogres, and therefore other Giants may be susceptible. If a creature dies while infected with darakhul fever, roll a `d20`, add the character's Constitution modifier, and find the result on the Adjustment Table below to determine what Undead form the victim's body rises in.
> 
> | Roll | Result |
> |------|--------|
> | 1-9 | None; victim is simply dead |
> | 10-16 | Ghoul |
> | 17-20 | Ghast |
> | 21+ | Darakhul |
> ^roll-result
^darakhul-fever

## Statblock

```ad-statblock
title: Darakhul
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ToB1-2023/Darakhul.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 18 ([scale mail](/Systems/5e/items/scale-mail.md), [shield](/Systems/5e/items/shield.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|17 (+3)|14 (+2)|14 (+2)|12 (+1)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +3, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](/Systems/5e/rules/conditions.md#charmed), [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** Common, Darakhul
- **Challenge** 3

## Traits

***Hungry Dead Nature.*** The darakhul requires no air or sleep.

***Master of Disguise.*** A darakhul in a prepared disguise has advantage on Charisma ([Deception](/Systems/5e/rules/skills.md#Deception)) checks made to pass as a living creature. While using this ability, it loses its Stench.

***Stench.*** Any creature that starts its turn within 5 feet of the darakhul must succeed on a DC 12 Constitution saving throw or be [poisoned](/Systems/5e/rules/conditions.md#poisoned) until the start of its next turn. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the darakhul's Stench for the next 24 hours. A darakhul using this ability can't also benefit from Master of Disguise.

***Sunlight Sensitivity.*** While in sunlight, the darakhul has disadvantage on attack rolls, as well as on Wisdom ([Perception](/Systems/5e/rules/skills.md#Perception)) checks that rely on sight.

***Turning Defiance.*** The darakhul and any ghouls within 30 feet of it have advantage on saving throws against effects that turn Undead.

## Actions

***Multiattack.*** The darakhul makes one Bite attack, one Claw attack, and one War Pick attack. If the darakhul is using a shield, it instead makes one Bite attack and one Claw or War Pick attack.

***Bite.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 12 (`2d8 + 3`) piercing damage, and, if the target is a Humanoid, it must succeed on a DC 11 Constitution saving throw or contract the darakhul fever disease.

***Claw.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 10 (`2d6 + 3`) slashing damage. If the target is a creature other than an Undead, it must succeed on a DC 12 Constitution saving throw or be [paralyzed](/Systems/5e/rules/conditions.md#paralyzed) for 1 minute. A [paralyzed](/Systems/5e/rules/conditions.md#paralyzed) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a Humanoid is [paralyzed](/Systems/5e/rules/conditions.md#paralyzed) for more than 2 rounds, it contracts darakhul fever.

***War Pick.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 7 (`1d8 + 3`) piercing damage.
```
^statblock

## Environment

underdark, urban