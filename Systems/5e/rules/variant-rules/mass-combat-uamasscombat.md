---
obsidianUIMode: preview
cssclasses: json5e-note
tags:
- compendium/src/5e/uamasscombat
aliases: ["Mass Combat"]
---
# Mass Combat
*Source: Unearthed Arcana: Mass Combat p. 1* 

The mass combat rules are designed to allow you, the DM, to determine the outcome of battles involving hundreds of combatants with a few die rolls. It also zooms down into the action with enough detail to allow player characters the chance to affect the outcome of a battle.

The system works by giving each creature a battle rating based on the creature's challenge rating. Battle rating is an abstract measure of a creature's combat effectiveness.

To make managing hundreds, or even thousands, of creatures at a time easier, creatures in the mass combat system are organized into units. A unit might include hundreds of individuals.

Each unit involved in a battle also has a morale rating. Morale measures the unit's motivation to engage in battle. Units with high morale are willing to fight to the death, while ones with low morale are likely to fall apart in the face of adversity.

Commanders play a key role in resolving battles. Each unit has a commander, whose Charisma modifiers applies to initiative and morale.

## Battle Rating

The mass combat rules rely on a creature's battle rating (BR) to summarize its effectiveness in combat. A creature's BR is based on its challenge rating (CR), as shown in the Battle Rating by Challenge Rating table. BR encompasses a creature's attacks, hit points, AC, and special abilities by relying on CR as a summary of its power.

BR starts as a bonus, from +1 to +50. A creature of CR 1 or lower is too weak to provide a BR on its own. The table shows that such creatures provide a +1 bonus when they gather in large enough groups. For instance, five CR 1/2 creatures provide a BR of +1. Smaller groups of CR 1/2 creatures provide no BR.

In combat, a unit's BR can be reduced by being attacked, going as low as 0 or a negative number. See the "Attacks" section later in these rules for details.

**Battle Rating by Challenge Rating**

| CR | BR |
|----|----|
| 1/8 | +1 per 20 creatures |
| 1/4 | +1 per 10 creatures |
| 1/2 | +1 per 5 creatures |
| 1 | +1 per 2 creatures |
| 2 | +1 |
| 3 | +2 |
| 4 | +3 |
| 5 | +4 |
| 6 | +5 |
| 7 | +6 |
| 8 | +8 |
| 9 | +10 |
| 10 | +12 |
| 11 | +16 |
| 12 | +18 |
| 13 | +22 |
| 14 | +26 |
| 15 | +30 |
| 16 | +34 |
| 17 | +38 |
| 18 | +42 |
| 19 | +46 |
| 20 | +50 |
^battle-rating-by-challenge-rating

## Creating Units

A unit is a single, cohesive group of soldiers that is organized to fight together. A unit can comprise up to 400 Tiny, Small, or Medium creatures. Larger creatures take up more space when counting toward that limit, as shown in the Creature Size in Units table. To count toward a unit's limit, a creature must have a BR.

**Creature Size in Units**

| Size | Space in Unit |
|------|---------------|
| Tiny | 1 |
| Small | 1 |
| Medium | 1 |
| Large | 4 |
| Huge | 9 |
| Gargantuan | 16 |
^creature-size-in-units

For example, a unit could include 50 Large creatures and 200 Medium ones. The total space taken up is 400, 200 for the Large creatures and 200 for the Medium ones.

### Commanders

Each unit must have a commander. The commander needs to be one of the creatures included in the unit but does not count toward determining the unit's size. Note the commander's Charisma modifier.

### BR Total

Once you have created a unit, total up the BR values of its creatures, including its commander. The total is the unit's BR.

For creatures that are mounted, such as knights riding a horse, add the BR for the mounts based on their CR, just as you would for any other creatures.

### Unit Space

A unit takes up a space that measures 100 feet on each side regardless of how many creatures are in it. The unit's size is an abstraction to make tracking units on the battlefield easy in play.

### Ranged Attackers

A unit can make ranged attacks if all its members, other than its commander, can make an attack with a range of at least 100 feet on an at-will basis. If this is the case, note the shortest maximum range of its members' ranged attacks. This is the unit's maximum range.

> [!note] Unit Design
> 
> It's best to organize similar or identical creatures into a unit. The rules aim to remain simple by reducing a unit's abilities to the lowest common denominator.
^unit-design

## Morale Rating

Morale is a rating like an ability score modifier. It ranges from -10 to +10. These rules sometimes require a unit to make a check using its morale rating; roll a `d20`, add the unit's morale rating, and compare the total to the relevant DC, just as for an ability check.

You select a morale rating for each unit involved in a battle. Assign the rating based on how the unit has been treated by its allies and commanders, the stakes of the battle, the unit's investment in the outcome, and any other factors that you think should play a role.

**Morale Ratings**

| Morale | Description |
|--------|-------------|
| -10 | Openly rebellious |
| -8 | Mutinous |
| -4 | Disgruntled |
| -2 | Shaky |
| 0 | The typical unit |
| +2 | Motivated |
| +4 | Stalwart |
| +8 | Fanatic |
| +10 | Unbreakable |
^morale-ratings

As a rule of thumb, start a unit's morale at 0 on the Morale Ratings table. For each factor that decreases the unit's morale, shift one row up the table. For each factor that improves it, shift one row down. When you're done with this exercise, you have a good idea of the unit's morale rating. Or you can simply assign a morale rating based on your judgment.

Finally, you alter the morale rating based on the unit commander's Charisma modifier. Add the commander's Charisma modifier to the unit's morale, to reflect the commander's ability to motivate and lead.

### Factors Affecting Morale

Here are some of the factors that can reduce a unit's morale rating:

- poor treatment by a commander or allies  
- animosity toward an allied unit  
- low or no pay  
- no stake in the battle's outcome  
- incompetent or ill-prepared commanders  
- a daunting, overwhelming foe  
- poor equipment  

The reverse of any of those factors can improve morale.

## Running Battles

These rules use a structure like the combat rules in the "Player's Handbook". The biggest change centers on resolving attacks, which uses BR rather than attack rolls, AC, and damage.

### Time

The mass combat rules use a timescale different from the regular combat rules, with 1 round representing 1 minute of action. This timescale accounts for the time and complexity needed to maneuver hundreds or even thousands of combatants.

### Initiative

You don't roll initiative for units. Instead, each unit has a fixed initiative:

Initiative 10 + unit morale rating + commander's Charisma modifier

Units act in order of initiative, from highest to lowest as normal. In the event of a tie, randomly determine the order in which the tied units act. Determine this once, and then use that order for the rest of the combat.

As in the regular combat rules, a unit can move and take one action on its turn (see "Action Options" below). A unit can use some or all of its movement before taking its action, and can then use the rest of its movement after acting

### Speed

A unit's speed equals 10 times the lowest speed of its members. It can use movement modes, such as flight, only if every member of the unit can use it. Don't count the speed of mounted creatures when determining the unit's speed and movement types. The riders use their mounts to move.

#### Movement

A unit must stop moving if it moves adjacent to an enemy unit, and a unit can't move if it is adjacent to an enemy unit, unless it uses the [Disengage](/Systems/5e/rules/actions.md#Disengage) action that turn. Otherwise, use the rules for movement from the "Player's Handbook" to resolve how far a unit can move.

#### Miniatures

It helps to use miniatures to track battles of great size. For these rules, use a grid or hexes with each square/hex measuring 100 feet on a side and with one miniature per unit. When moving, a unit can move into a square/hex if the unit has at least half the movement needed to enter it available.

### Action Options

When a unit takes its action, it chooses one of the following action options: [Attack](/Systems/5e/rules/actions.md#Attack), Dash, Defend, [Disengage](/Systems/5e/rules/actions.md#Disengage), or Guard. Each option is described below.

#### Attack

An attack is an opposed check between a unit's BR and its target's BR. A unit can attack at any range that all of its members can make attacks at. Full details on resolving attacks are given in the "Attacks" section below.

#### Dash

A unit that dashes increases its speed for its turn. This increase equals the unit's speed.

#### Defend

A unit that defends focuses on building a shield wall or otherwise making itself harder to hurt. Until the end of its next turn, units that attack it suffer disadvantage on their BR checks.

#### Disengage

A unit that is adjacent to an enemy unit normally can't move. If the unit takes the [Disengage](/Systems/5e/rules/actions.md#Disengage) action, it has the chance to move away. The unit must immediately make a DC 10 morale check. If it fails, it loses its action and doesn't move. If it succeeds, it can move up to half its speed. During this move, it doesn't need to stop if it moves adjacent to an enemy unit.

#### Guard

A unit that guards prepares to attack any enemy that draws close to it. The next time an enemy unit enters a space adjacent to this unit, it immediately makes an attack against the enemy unit.

### Attacks

Attacks in the mass combat rules use opposed BR checks to determine which side has the upper hand.

A unit can attack an adjacent enemy unit if any creature in the unit is within 5 feet of the target. It can make an attack at range if all its members can make ranged attacks that can reach the target.

When a unit attacks a target, the attacking unit rolls a `d20` and adds its BR, as does the target. You then compare the results to determine the result of the fight:

- **Tie.** Nothing happens if the attacker and the target tie.  
- **Target Wins.** If the target's total is higher, the attack has no effect.  
- **Attacker Wins by 10 or Less.** The attacker scores casualties, but not enough to break the target unit. The target's BR is reduced by 2.  
- **Attacker Wins by 11 or More.** The attacker scores heavy casualties on the target. The target's BR is reduced by 5, and it must immediately make a DC 10 morale check. If the check fails, the unit flees the battle and is eliminated. Remove it from play.  

The attacker can gain advantage or suffer disadvantage on its BR roll, based on the following factors:

- The attacker is on higher ground, such as uphill from the defender.  
- The defender is adjacent to at least one enemy unit, other than the attacker.  

- The defender is partially behind a wall or similar cover.  
- The defender is adjacent to at least two friendly units.  

### Abstraction and Battle Rating

Remember that the mass combat rules are designed to make running big, important battles fast and easy. It uses BR to summarize a creature's spells, special abilities, and so on. There are no special rules for resistance or spell casting because the rules assume that CR has already accounted for them.

### Morale Checks

In addition to the morale checks caused by certain actions, a unit must make a morale check if certain conditions occur during the battle:

- **Casualties.** If a unit is reduced to half or less of its starting BR, it must immediately make a DC 15 morale check. If it fails, it is eliminated from the battle. Remove it from play.  
- **Friendly Casualties.** If a friendly unit within 500 feet of the unit is eliminated, the unit must immediately make a DC 10 morale check. If it fails, the unit can't move or take actions on its next turn.  

## Characters in Mass Combat

The real fun of running a mass battle is giving player characters and important NPCs a chance to affect the outcome. You might be tempted to absorb such characters into units and ignore their special abilities. You can do so by using the rules for determining CR in the *Dungeon Master's Guide* to assign CRs to the characters. However, mass battles are more fun for players when they have a chance to engage in heroics that alter the course of the fight.

You can give the characters an opportunity to shine by pausing the large-scale battle and letting them engage in a regular combat (see "Character-Scale Combat" below) or by letting them use their abilities from within a unit (see "Characters in Units below).

### Character Abilities

Whatever way the characters are involved in a mass combat, resolve their features, spells, and other abilities using the standard rules, rather than the mass combat rules. For example, a wall of ice can block a 100-foot long line. If a unit moves next to it, use the individual members' stats to make their saving throws and apply damage. If members of a unit are killed, recalculate the unit's BR after removing the casualties.

Adjudicating these effects requires your judgment as DM. Consider the nature of the situation, how a unit interacts with a spell or other effect, and apply the effects as you see fit. Going back to wall of ice, you might judge that 30 creatures from a unit attempt to smash it down. Those creatures suffer the wall's effects, but they also have a chance to damage it. Use the rules for handling mobs on page 250 of the *Dungeon Master's Guide* to speed things up.

### Character-Scale Combat

You can think of the mass combat rules as looking at a battle from high altitude. You lose detail but can see and manage the big picture. When PCs take part in a battle, your view can zoom down to experience the action in more detail.

When characters battle units, you can use the standard combat rules, with the guidelines for resolving mob attacks (see "Handling Mobs" in the *Dungeon Master's Guide*, page 250).

You may decide that all or part of a unit stops to fight the PCs. Pause the mass battle, and resolve the characters' fight like a normal combat, until you are satisfied that you have reached a conclusion, with either side defeated or driven off. You can then resume the mass combat.

### Characters in Units

If the characters join a unit, don't include them in the unit's size or BR calculation. Instead, when the unit attacks, allow the characters to make their own separate attacks, cast spells, and to use magic items against the enemy unit using the guidelines given above. Allow them to pick out which members of the unit they want to target, in case the unit is composed of several types of creatures. Characters attacking in this manner can target only creatures included in the target unit's BR.

On the unit's turn, each character has one turn to make attacks, cast spells, use a magic item, or the like. Resolve the characters' attacks and spells and determine how many targets they eliminate. Determine how the loss of those creatures reduces the unit's BR, then resolve the unit fight as normal.

If a spell or effect leaves a creature unable to move or take actions, count that creature as eliminated for the rest of the battle.

If the characters' unit comes under attack, resolve the fight as normal. The results don't apply to the characters. If their unit is eliminated, they remain on the battlefield and can continue to act.

### Critical Events

In addition to allowing characters to take part in fights between units, think of critical events that might take place during the battle and give characters a chance to take part in those events. Critical events can include the following:

- Prevent enemy scouts from seizing a bridge or other position.  
- Assassinate an enemy commander.  
- Hold attackers away from a gate while friendly soldiers repair it.  
- Sneak into an enemy stronghold to sabotage its defenses.  
- Destroy an approaching siege engine.  
- Steal the enemy's battle plans.  

These critical events play out just like short adventures. You should map the area, determine the opposition, and prepare any NPCs as needed. When creating critical events, think about the consequences for success and failure. What happens if the PCs manage to destroy a bridge the enemy needs to cross a river? If the PCs don't raise the castle gates by dawn, what happens next?

The situation at the start of a clash could be dictated by the PCs' success or failure beforehand. An enemy unit might start a battle in a strong position, lurking in a village with cover, because the PCs failed to outmaneuver them. Or the PCs might destroy an evil wizard's castle gate, rendering his fortification useless in the coming battle.

> [!note] NPCs, PCs, and Battle Rating
> 
> You can always calculate a character's BR and simply include it in a unit, though the level of abstraction in the rules removes individual actions from a player's control. This approach is best for NPCs who are commanders or who are background players in the battle.
> 
> Treat critical NPCs, such as important villains and rivals, in the same way you would manage PCs. Let the players seek them out, for the clash between them is undoubtedly a critical event in determining how the battle unfolds.
^npcs-pcs-and-battle-rating