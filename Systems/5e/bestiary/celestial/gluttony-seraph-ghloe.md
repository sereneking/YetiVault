---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/14
- monster/size/huge
- monster/type/celestial
aliases: ["Gluttony Seraph"]
---
# Gluttony Seraph
*Source: Grim Hollow: Lairs of Etharis p. 95*  

> [!quote]-  
> 
> Don't go to the temple. Something sinister has claimed it. Seek shelter elsewhere.

## Salvage

An avarice seraph's metal-tipped feathers can be sold. Those of the lesser seraph are worth 250 gp, while those of the seraph are worth 1,000 gp.

Someone who has proficiency with alchemist's supplies can melt the metal on the feathers of an avarice seraph and use some feathers as fletching to make one arrow of celestial slaying for a lesser seraph, or four such arrows from the seraph. Making one arrow takes 7 days of work, reagents worth 1,000 gp, and a successful DC 17 Intelligence or Wisdom check.

The saliva of a gluttony seraph functions as antitoxin—three doses can be collected from a lesser seraph, while ten can be gathered from a seraph. Someone who has proficiency with alchemist's supplies or an herbalism kit can mix two doses of this saliva with reagents worth 50 gp and brew the mixture for 4 hours. The resulting elixir affects the imbiber as a protection from poison spell, curing a random poison in the drinker's system.

## Lore

- **DC 10 Intelligence ([History](/Systems/5e/rules/skills.md#History)).** The disavowed are seraphs fallen to evil. Each still retains a measure of its celestial power.  
- **DC 15 Intelligence ([Religion](/Systems/5e/rules/skills.md#Religion)).** From their celestial heritage, disavowed retain magic resistance and resistance to nonmagical attacks, as well as immunity to being charmed, exhausted, and frightened. Even in a fallen state, the seraph imparts magic and radiant damage to its attacks. Gluttony seraphs are also immune to poison.  
- **DC 20 Intelligence ([Arcana](/Systems/5e/rules/skills.md#Arcana)).** Avarice seraphs can rouse the greed in any creature. Huge gluttony seraphs can swallow and digest people, although their lesser kin can't.  

## Statblock

```ad-statblock
title: Gluttony Seraph
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GHLoE/Gluttony%20Seraph.webp#token)
*Huge celestial, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 218 (`19d12 + 95`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|12 (+1)|20 (+5)|13 (+1)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10, Wisdom +7, Charisma +8
- **Skills** Insight +7, Perception +7
- **Senses** truesight 120 ft., passive Perception 17
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](/Systems/5e/rules/conditions.md#charmed), [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [frightened](/Systems/5e/rules/conditions.md#frightened), [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 14

## Traits

***Magic Resistance.*** The seraph has advantage on saving throws against spells and other magical effects.

***Seraphic Weapons.*** The seraph's weapon attacks are magical. When the seraph hits with any weapon, the weapon deals an extra (`2d8`) radiant damage (included in the attacks).

***Innate Spellcasting.*** The seraph's spellcasting ability is Charisma (spell save DC 16). The seraph can innately cast the following spells, using only verbal components:

**At will**: [detect evil and good](/Systems/5e/spells/detect-evil-and-good.md), [detect magic](/Systems/5e/spells/detect-magic.md), [light](/Systems/5e/spells/light.md), [thaumaturgy](/Systems/5e/spells/thaumaturgy.md)

**1/day**: [create food and water](/Systems/5e/spells/create-food-and-water.md) (the food is tasty and the seraph can create wine instead of water)

**3/day**: [suggestion](/Systems/5e/spells/suggestion.md)

## Actions

***Multiattack.*** The seraph makes three attacks, only one of which can be a bite.

***Bite.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one target. *Hit:* 24 (`3d12 + 5`) piercing damage and 9 (`2d8`) radiant damage. If the target is a Large or smaller creature, it is [grappled](/Systems/5e/rules/conditions.md#grappled) (escape DC 18). Until this grapple ends, the target is [restrained](/Systems/5e/rules/conditions.md#restrained), and the seraph can't bite another target.

***Claw.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one target. *Hit:* 12 (`2d6 + 5`) slashing damage and 9 (`2d8`) radiant damage.

***Tongue.*** *Melee Weapon Attack:* `+10` to hit, reach 20 ft., one creature. *Hit:* 10 (`2d4 + 5`) bludgeoning damage and 9 (`2d8`) radiant damage, and the target is [grappled](/Systems/5e/rules/conditions.md#grappled) (escape DC 18) and pulled to within 5 feet of the seraph. Until the grapple ends, the target is [restrained](/Systems/5e/rules/conditions.md#restrained), and the seraph can't use its tongue or bite on another target.

***Swallow.*** The seraph makes one bite attack against a Medium or smaller creature it holds [grappled](/Systems/5e/rules/conditions.md#grappled). If the attack hits, the target takes the bite's damage, the grapple ends, and the target is swallowed. While swallowed, a creature is [blinded](/Systems/5e/rules/conditions.md#blinded) and [restrained](/Systems/5e/rules/conditions.md#restrained), has total cover against anything originating outside the seraph, and takes 18 (`4d8`) acid damage and 9 (`2d8`) radiant damage at the start of each of the seraph's turns. The seraph can have only one creature swallowed at a time.

If the seraph takes 35 damage or more on a single turn from a creature inside it, the seraph must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls [prone](/Systems/5e/rules/conditions.md#prone) in a space within 10 feet of the seraph. If the seraph dies, the swallowed creature is no longer [restrained](/Systems/5e/rules/conditions.md#restrained) by it and can escape the corpse by using 10 feet of movement, exiting [prone](/Systems/5e/rules/conditions.md#prone).
```
^statblock