---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Corpse Walker"]
---
# Corpse Walker
*Source: Grim Hollow: Lairs of Etharis p. 103*  

> [!quote]-  
> 
> They rose from their graves, some by force of magic, others cursed through their life's misdeeds. Whatever the reason, we can't let them walk among the living.

## Salvage

Someone who has proficiency with alchemist's supplies can mix the mold from a corpse walker's skin with other materials worth 500 gp to produce a potion that grants all the corpse walker's damage resistances for 10 minutes. The skin from an ancient corpse walker can produce two doses of this potion. A humanoid that dies while under the effects of this potion rises as a corpse walker 24 hours later. Creating this rare potion requires a successful DC 15 Intelligence ([Religion](/Systems/5e/rules/skills.md#Religion)) check and 8 hours of brewing.

Someone who has proficiency with smith's tools can fashion the femur of an ancient corpse walker into a one-handed melee weapon. Both femurs can make a two-handed weapon. Creating the weapon takes 10 days and extra materials worth 500 gp, and it's a magic weapon when complete. Someone you hit with an attack using the weapon can't regain hit points until the start of your next turn. If someone casts vampiric touch and inflict wounds on the weapon once per day while it's being made, and materials worth 1,000 more gp are added to the process, the weapon also takes on the properties of a sword of life stealing but need not be a sword.

## Lore

- **DC 10 Intelligence ([History](/Systems/5e/rules/skills.md#History)).** It's bad luck for the living to set eyes upon a corpse walker. The returned gaze imparts a curse. Like a zombie, a corpse walker can take significant wounds and remain standing.  
- **DC 15 Intelligence ([Religion](/Systems/5e/rules/skills.md#Religion)).** The corpse walker has a severe vulnerability to sunlight, which burns and distracts it. Radiant damage is a sure way to ensure the corpse walker stays down when slain.  
- **DC 20 Intelligence ([Arcana](/Systems/5e/rules/skills.md#Arcana)).** An ancient corpse walker can release spores that call loyal undead to it, although wind can disperse these spores. The ancient walker can also become a cloud of deadly spores that can animate corpses. If terribly wounded, the ancient corpse walker turns into this mist and has 2 hours to return to its lair or perish forever.  

## Statblock

```ad-statblock
title: Corpse Walker
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/GHLoE/Corpse%20Walker.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|13 (+1)|17 (+3)| 6 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +3
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](/Systems/5e/rules/conditions.md#exhaustion), [poisoned](/Systems/5e/rules/conditions.md#poisoned)
- **Languages** understands languages it knew in life but can't speak
- **Challenge** 6

## Traits

***Cursed Gaze.*** A humanoid that starts its turn within 30 ft. of and able to see the corpse walker must succeed on a DC 14 Charisma saving throw, provided the corpse walker isn't [incapacitated](/Systems/5e/rules/conditions.md#incapacitated). On a failure, the humanoid is [frightened](/Systems/5e/rules/conditions.md#frightened) for 1 minute. A [frightened](/Systems/5e/rules/conditions.md#frightened) target can repeat the saving throw at the end of each of its turns, with disadvantage if not averting its eyes from the corpse walker, ending the effect on itself on a success. A creature failing two of these saving throws becomes cursed with disturbing thoughts. Such a creature can't benefit from a short or long rest until the curse is removed. On a successful save, the target is immune to any corpse walker's Cursed Gaze for the next 24 hours.

Unless surprised, a creature can avert its eyes to avoid the saving throw. If the creature does so, it can't see the corpse walker until the start of its next turn. A creature that looks at the corpse walker in the meantime must immediately make the save.

***Sunlight Hypersensitivity.*** The corpse walker takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

***Undead Fortitude.*** If damage reduces the corpse walker to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the corpse walker drops to 1 hit point instead.

## Actions

***Multiattack.*** The corpse walker makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `+6` to hit, reach 5 ft., one target. *Hit:* 7 (`1d6 + 4`) bludgeoning damage and 5 (`2d4`) necrotic damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the necrotic damage taken, and the corpse walker regains hit points equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. An evil humanoid slain this way rises 24 hours later as a corpse walker.
```
^statblock