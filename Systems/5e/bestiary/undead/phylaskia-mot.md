---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/9
- monster/size/large
- monster/type/undead
aliases: ["Phylaskia"]
---
# Phylaskia
*Source: Mythic Odysseys of Theros p. 239*  

These armored skeletal spirits guard the borders of the Underworld and its various wards. Sleepless and merciless, they scrutinize all who would pass, and they slay those who defy them.

```ad-statblock
title: Phylaskia
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MOT/Phylaskia.webp#token)
*Large undead, Lawful Neutral*

- **Armor Class** 18 ([plate](/Systems/5e/items/plate-armor.md))
- **Hit Points** 104 (`11d10 + 44`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|18 (+4)|10 (+0)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +7
- **Skills** Insight +7, Perception +7
- **Senses** truesight 120 ft., passive Perception 17
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [blinded](/Systems/5e/rules/conditions.md#blinded), [charmed](/Systems/5e/rules/conditions.md#charmed), [deafened](/Systems/5e/rules/conditions.md#deafened), [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [frightened](/Systems/5e/rules/conditions.md#frightened), [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** all
- **Challenge** 9

## Traits

***Gatekeeper's Aura.*** Any creature that starts its turn within 10 feet of the phylaskia must make a DC 15 Wisdom saving throw. On a successful save, the creature is immune to this aura for the next 24 hours. On a failed save, the creature has disadvantage on saving throws and its speed is halved until the start of its next turn.

***Undead Fortitude.*** If damage reduces the phylaskia to 0 hit points, it must make a Constitution saving throw with a DC equal to 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the phylaskia drops to 1 hit point instead.

***Vigilant.*** The phylaskia can't be [surprised](/Systems/5e/rules/conditions.md#surprised).

## Actions

***Multiattack.*** The phylaskia makes two longsword attacks and uses its Strength Drain once.

***Longsword.*** *Melee Weapon Attack:* `+9` to hit, reach 10 ft., one target. *Hit:* 14 (`2d8 + 5`) slashing damage, or 16 (`2d10 + 5`) slashing damage if used with two hands, plus 11 (`2d10`) necrotic damage.

***Strength Drain.*** *Melee Weapon Attack:* `+9` to hit, reach 5 ft., one creature. *Hit:* 12 (`2d6 + 5`) necrotic damage. Unless the target is immune to necrotic damage, its Strength score is reduced by `1d4`. The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest.
```
^statblock