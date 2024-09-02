---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Living Burning Hands"]
---
# Living Burning Hands
*Source: Eberron: Rising from the Last War p. 298*  

## Constructed Nature

A living spell doesn't require air, food, drink, or sleep.

Of all the anomalies that emerged from the magical cataclysm that created the Mournland, the appearance of living spells might be the most mysterious. In some unknown fashion, the magical energy unleashed during the Last War caused spell effects to take on sentience. A living spell appears much like a normal spell effect, except that its magical energy endures indefinitely.

Living spells haunt the Mournland and other areas blasted by the Last War, somehow subsisting on ambient magical energy as they writhe and across the landscape. Though they have no need for sustenance, they attack any creatures they come into contact with, lashing out indiscriminately with their corrupted magic.

## Customizing a Living Spell

Living spells come in many varieties; the stat blocks here are three examples. Living spells most often manifest from evocation and conjuration spells. To make a living spell from a different spell, choose a damage-dealing evocation or conjuration spell from the wizard spell list of up to 5th level. Then consult the Living Spell Customization table to see which stat block to customize, based on the chosen spell's level.

**Living Spell Customization**

| Spell Level | Stat Block to Customize |
|-------------|-------------------------|
| 1–2 | Living burning hands |
| 3–4 | Living lightning bolt |
| 5 | Living cloudkill |
^living-spell-customization

Now make the following changes to that stat block:

**Damage Immunity**. Replace the living spell's damage immunity with immunity to the type (or types) of damage dealt by the chosen spell.

**Magical Strike**. Replace the damage that Magical Strike deals with one type of damage dealt by the chosen spell.

**Spell Mimicry**. Replace the effect of Spell Mimicry with the effect of the chosen spell. If that spell requires a saving throw, use spell save DC from the replaced spell, and if the spell involves an attack roll, use the attack bonus from the living spell's Magical Strike.

For example, if you turn [fireball](/Systems/5e/spells/fireball.md) (a 3rd-level spell) into a living spell, customize the [living lightning bolt](/Systems/5e/bestiary/construct/living-lightning-bolt-erlw.md). The living fireball has immunity to fire damage, instead of lightning damage; deals fire damage with its Magical Strike; and replicates [fireball](/Systems/5e/spells/fireball.md) with Spell Mimicry.

## Statblock

```ad-statblock
title: Living Burning Hands
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/ERLW/Living%20Burning%20Hands.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 15 (`2d8 + 6`)
- **Speed** 25 ft., fly 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|12 (+1)|16 (+3)| 3 (-4)| 6 (-2)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire
- **Condition Immunities** [blinded](/Systems/5e/rules/conditions.md#blinded), [charmed](/Systems/5e/rules/conditions.md#charmed), [deafened](/Systems/5e/rules/conditions.md#deafened), [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [frightened](/Systems/5e/rules/conditions.md#frightened), [grappled](/Systems/5e/rules/conditions.md#grappled), [poisoned](/Systems/5e/rules/conditions.md#poisoned), [prone](/Systems/5e/rules/conditions.md#prone)
- **Languages** —
- **Challenge** 1

## Traits

***Amorphous.*** The living spell can move through a space as narrow as 1 inch wide without squeezing.

***Magic Resistance.*** The living spell has advantage on saving throws against spells and other magical effects.

## Actions

***Magical Strike.*** *Melee Spell Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 6 (`1d6 + 3`) fire damage.

***Spell Mimicry (Recharge 5-6).*** The living spell unleashes a thin sheet of flames in a 15-foot cone. Each creature in that area must make a DC 13 Dexterity saving throw, taking 10 (`3d6`) fire damage on a failed save, or half as much damage on a successful one.
```
^statblock