---
obsidianUIMode: preview
cssclasses: json5e-note
tags:
- compendium/src/5e/uagreyhawkinitiative
aliases: ["Greyhawk Initiative"]
---
# Greyhawk Initiative
*Source: Unearthed Arcana: Greyhawk Initiative p. 1* 

## Overview

The Greyhawk initiative variant institutes the following rules, which replace the standard initiative system.

### Rounds

Combat is organized into rounds. Each round, everyone involved in the combat has a chance to move and take actions, as with standard initiative. But the durations of effects are measured in rounds, rather than ending during a specific creature's turn.

### Variable Turn Order

Each round, every creature involved in the battle rolls initiative. The order in which creatures take their turns changes from round to round, making it impossible to predict how events in combat will unfold.

### Initiative Dice

Rather than making a `d20` roll for initiative, characters and monsters might roll a variety of initiative dice—normally `d4` to `d10`. If you roll more than one initiative die, you add the results together to determine your initiative. The number and type of initiative dice you roll depend on the types of activities you want your character to undertake during the next round.

### Initiative Count

Under the standard system, creatures with higher initiative have a chance to act each round before creatures with lower initiative. With this variant system, **initiative now runs from low to high**. Creatures with a lower initiative roll can act in combat before creatures with a higher initiative roll.

### Order of Operations

These rules make it more likely for certain actions to take place earlier in a round, and for other actions to take place later. Missile fire usually occurs first, melee attacks next, and spellcasting last. This is just an overall pattern, though, not an ironclad rule. As with the standard initiative system, the luck of the dice always determines exactly when combatants act.

### Rounds

Combat under this system is divided into rounds, each of which continues to represent about 6 seconds of action.

#### Durations

Any effect that normally lasts until the end of a turn instead lasts until the end of the round during which that turn takes place. Similarly, any effect that normally lasts until the start of a turn now lasts until the start of the round during which that turn takes place. If the order in which effects end is important for some reason, roll a `d20` for each effect (rerolling any ties). The effect with the lowest roll ends first, with the others ending in order of their results from lowest to highest.

### Surprise

A surprised creature adds +10 to its initiative result and cannot take reactions while it is surprised. A creature is surprised until the end of the round during which it is surprised.

### Determine Action Order

Before a round begins, each creature involved in a combat decides what it wants to do and rolls initiative. Your chosen actions determine which initiative dice you roll.

Actions are broken down by speed. Because a lower initiative count allows a creature to act more quickly, fast or simple actions use smaller dice and more complex actions use larger dice.

When rolling initiative, you roll all the dice that represent your actions, then add up the result. You do not add any modifier (including your Dexterity modifier) to this roll.

**Initiative Dice**

| Die | Action |
|-----|--------|
| `d4` | Ranged attack |
| `d6` | Movement |
|  | Swap gear |
|  | Any other action |
| `d8` | Melee attack |
| `d10` | Cast a spell |
^initiative-dice

#### Multiple Dice

It is common for characters to roll multiple dice for initiative. If you want to move in toward a foe and make a melee attack, you roll and add together `1d6` for movement and `1d8` for the attack. The result is your initiative.

> [!note] Variant: Weapon Speed
> 
> If you want to add more distinction to weapons at the cost of speed, replace rolling a `d4` for ranged attacks and a `d8` for melee attacks with the following:
> 
> When determining initiative, a creature attacking with a weapon rolls initiative dice equal to the damage dice rolled for the weapon. Use the base damage listed in the [Weapons](/Systems/5e/tables/weapons.md) table in chapter 5 of the "Player's Handbook", ignoring additional damage granted by spells, magical effects, feats, and so on.
^variant-weapon-speed

#### Bonus Actions

If you want to use a bonus action on your turn, you roll an additional die that corresponds to the type of action you plan to take with your bonus action. That die is added to any dice you roll for your movement and your normal action.

#### Multiple Actions

If an effect grants you an additional action without the use of a bonus action, you roll an initiative die for only one of your actions. Use the largest die that corresponds to any one of the actions you plan to take.

#### Reactions and Forced Activities

Initiative covers only the actions you take on your turn, so that using a reaction has no effect on your initiative. You can take one reaction per round, as normal, unless an ability grants you more. Likewise, any activities you are forced to undertake not on your turn (typically in response to another creature's actions) have no effect on your initiative.

#### Delaying

You cannot use the [Ready](/Systems/5e/rules/actions.md#Ready) action under these rules, but you can instead choose to delay your turn. Instead of taking your turn on your initiative count, you simply act on a later initiative count, before or after other creatures as you choose. If more than one creature has chosen to delay, each creature's original initiative needs to be noted. Whenever a delaying creature decides to act, another delaying creature with a lower initiative can decide to act immediately before it.

#### Swapping Gear

If you want to sheathe or drop a weapon, you roll an additional `1d6` for your initiative. You can decide to swap your gear at any point during your turn.

### Creatures Unable to Act

Any creature that is unable to take actions (most likely because it is [incapacitated](/Systems/5e/rules/conditions.md#incapacitated)) does not roll initiative. Any effects that such creatures must resolve, such as death saving throws, are resolved at the end of the round.

### Choosing Another Creature's Actions

If you are in a position to choose the actions that another creature takes on its turn (for example, if you have successfully targeted that creature with the [dominate monster](/Systems/5e/spells/dominate-monster.md) spell), you roll initiative for the actions you plan to have the creature take, then add that result to your initiative. The final result is the creature's initiative.

In general, if an effect causes a creature to change its actions and it has not yet taken a turn, the creature rerolls its initiative and adds the result to the initiative of the creature or effect that triggered the change.

### Action Declaration and Resolution

At the start of a round, each combatant chooses actions for the round. At this stage, actions do not need any more detail than what is needed to determine the initiative roll. A character can plan on casting a spell, but does not yet need to pick a specific spell or a target. A character planning on moving doesn't need to have a destination in mind.

During its turn, each combatant then chooses specific targets, spells, and so on for its chosen actions. The only restriction is that a creature cannot choose actions not covered by its initiative roll. As such, you might find that you need to alter the details of your plans as the action unfolds—meaning that it's often desirable to leave yourself options when you choose which actions to roll for.

### Ties

If two creatures tie for initiative, those creatures act in order of Dexterity, with the highest Dexterity going first. If both creatures have the same Dexterity, roll randomly to determine which one acts first.

> [!note] Variant: Spell Disruption
> 
> For added AD&D flavor, you can introduce the spell disruption rule. Under this rule, if a creature that wants to cast a spell takes damage during the round before it can act, it is restricted to casting cantrips on its turn.
^variant-spell-disruption

### Special Rules

Certain effects can alter initiative rolls in the game.

#### Initiative Bonuses or Penalties

Though this system does not apply a creature's Dexterity modifier to its initiative rolls, other effects can alter initiative. If an effect would grant you a bonus to your initiative roll under the standard system, instead reduce the size of one die you roll for initiative, so that a `d6` becomes a `d4`, a `d4` becomes a `d3`, and so on. In the case of a penalty to your initiative, you apply the reverse process, increasing the size of one die rolled instead.

#### Advantage or Disadvantage

If an effect would grant you advantage or disadvantage on your initiative roll under the standard system, you apply that to the largest initiative die you roll (or to one of those initiative dice if you roll more than one of the same type). Roll the initiative die twice, using the lowest roll if you have advantage or the highest roll if you have disadvantage.