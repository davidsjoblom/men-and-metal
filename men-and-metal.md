Men & Metal - Wargame Rules <!-- no toc -->

# 1. General Principles

## 1.1. Models

Models are physical representations soldiers and war machines.
A model consists of 2 parts; the base and the miniature:

- The base is a round plate of a specific dimension depending on the unit represented.
- The miniature, or miniatures, are mounted on the base and visually indicate the unit represented.

## 1.2. Model Interpretation

A model is always assumed to occupy the whole area of its base regardless of the physical miniatures mounted on it.
The miniature part is purely decorative and only the base is used for Line of Sight and measurement purposes.

## 1.3. Units

A unit consists of a number of models moving and fighting together.
Infantry are typically organized into units of 6 and vehicles into units of 3.

## 1.4. Unit Cohesion

All units have a Cohesion distance.
Typically 1" for infantry units and 2" for vehicle units.

A unit is considered to maintain Unit Cohesion when both of these conditions are fulfilled:

- All models are within Cohesion Distance of at least one other model in the unit
- All models are connected through an unbroken chain of other models in the unit

## 1.5. Unit Boundary

All units have a Unit Boundary.
This boundary is the area covered by the sum of all bases of models in the unit as well as the spaces between those models.
These spaces are the area swept over by a model should it make an imaginary move straight towards the other model and stopping right on top of it.
These spaces only occur between models that are within their Cohesion distance of each other.

Example:
A unit with Base size of 30mm would have a Unit Boundary consisting of the area covered by the units models as well as all 30mm wide area corridors between all pairs of models within Unit Cohesion distance.

Note that a Unit Boundary may fragment, for example as a result of removing casualties.

## 1.6. Armies

An army consists of a number of units controlled by a single player.
Friendly units are units belonging to the same army while enemy units are units belonging to the opposing players army.

## 1.7. The Battlefield

The Battlefield, also called the board, is the physical space where the game takes place.
The standard board size is 48" by 72".

### 1.7.1. Battlefield Interpretation <!-- no toc -->

For all rules purposes The Battlefield is considered a 2D plane.

## 1.8. Line of Sight

A model is considered to have Line of Sight to another model if an unobstructed straight line can be drawn from any point of its base to any point on the base of the other model.
A unit is considered to have Line of Sight to another unit if at least one model in the unit has Line of Sight to at least one model in the other unit.

Line of Sight drawn by or to a model is never obstructed by other models in its own unit.
The Unit Boundaries of intervening units obstruct Line of Sight.

Certain Terrain features obstruct Line of Sight, see Terrain section.

## 1.9. Measuring Distance

Distance between two models are measured in a straight line between the closest points of their respective bases.
Distance between two units is the distance between the two closest models from each the unit.
A unit is considered to be within a specified distance of something if the distance of its closest model is equal to or less than the specified distance.

Note that the vertical position of the physical models is ignored, all models are considered to be at the same level when measuring distance.
All distances are measured in inches.
Players are free to measure any distance at any time.

## 1.10. Dice

All dice used are ten-sided dice referred to as a D10.
A number in front refers to a number of dice, e.g. 2D10 calls for two D10s to be rolled.

## 1.11. Target Number

The Target Number, TN, is the value a rolled D10 needs to equal or be less than to be considered a success.
A roll that exceeds the TN is considered a fail.
A TN is calculated by taking the base TN and applying the relevant modifiers to it, e.g. a base TN of 3 with a +1 modifier results in a final TN of 4.

## 1.12. Tokens & Markers

Tokens and markers are physical gaming aids used to indicate various game related things.
Tokens and markers have no in-game presence and may be moved around to make space whenever necessary.

### 1.12.1. Order tokens <!-- no toc -->

Order tokens have a blank side while the other side features one of the Orders.
These are used to privately assign Orders by placing them face down next to a unit and then flipped up to reveal which Order was issued.
All Order tokens are removed after the unit has carried them out.
An exception to this is the Advance Order which is replaced instead.

### 1.12.2. Pin markers <!-- no toc -->

Pin markers, or simply Pins, are used to track the level of stress a unit is experiencing by placing an number of them next to the unit.
Pins follow along with the unit until they are removed.
Players should bring their own visually distinct pin markers in Order to make tracking pin numbers at a glance easy for their opponent.

### 1.12.3. Objective makers <!-- no toc -->

Objective markers are used to specify a point or a terrain feature on the battlefield as Objectives.
These are used in Scenarios to score Victory points.

### 1.12.4. Targeting Arrows <!-- no toc -->

Targeting arrows are used to declare targets.
They are placed in front of attacking units, pointed towards their declared target.

# 2. Unit Characteristics

All units have a number of characteristics that determine how they act on the the battlefield.
These are found in each unit's respective Unit Profile.

## 2.1. Unit Type <!-- no toc -->

Each unit has a Unit type.
Unit types has no in-game effect itself but influences how the unit interacts with other rules.

## 2.2. Model Number <!-- no toc -->

The number of models the unit consists of.

## 2.3. Cohesion Distance <!-- no toc -->

This distance is used to determine Unit Cohesion.

## 2.4. Base Size <!-- no toc -->

The diameter of the model's base.

## 2.5. Speed <!-- no toc -->

A unit's Speed determines how far it can move during a Move action.

## 2.6. Discipline <!-- no toc -->

A unit's Discipline represents its ability to keep fighting under pressure and shake off suppression.
Discipline determines the Target Number for Rally tests.

## 2.7. Range <!-- no toc -->

A unit's Range is the maximum distance that the unit can effectively attack.

## 2.8. Attacks <!-- no toc -->

The number of dice the model rolls when fighting.

## Power

The Target Number the unit needs to roll when fighting.
This number is commonly modified depending on battlefield conditions.

## 2.9. Special Rules <!-- no toc -->

Most units have one or more Special rules that effects their battlefield capabilities.

# 3. The Round

The game is played over a number of Rounds.
Each Round consists of a sequence of phases:

1. Command phase
   1. Issue Orders
   2. Reveal Orders
   3. Determine Starting player for the Round
2. Movement phase
3. Overwatch phase
   1. Declare targets
   2. Resolve attacks
   3. Remove casualties
4. Combat phase
   1. Declare targets
   2. Resolve attacks
   3. Remove casualties
5. Rally phase
   1. Take Rally tests
   2. Checks suppression
6. End phase
   1. Score Victory Points
   2. Check Victory Conditions

## 3.1. Command Phase

### 3.1.1. Assign Order Tokens <!-- no toc -->

Both players begin the Command phase by privately assigning all their units a single Order token each.
A unit may normally be assigned either an Advance, Overwatch or Sprint Order token.
If a unit is Suppressed then it may only be assigned either a Fight or a Move Order token instead.
Order tokens are placed face down next to the unit assigned them.

### 3.1.2. Reveal Order Tokens <!-- no toc -->

When both players are done all Order tokens are made public by flipping them face up.
Any unit that players forgot to assign an Order token before they were made public are automatically assigned a Fight Order token.

### 3.1.3. Determine Starting Player <!-- no toc -->

After Orders are assigned both players rolls a D10 each.
The player with the highest roll becomes the Starting player for this Round.
In case of a tie the player that was the Second player during the previous round becomes the Starting player for this Round.
The other player becomes the Second player for this Round.
If its the roll for the first round then ties are rerolled.

## 3.2. Movement Phase

The Starting player moves all his eligible units.
Then the Second player moves all his eligible units.
Eligible units are units with Advance, Sprint or Move Orders.
See the Movement section for details on how to move units.

## 3.3. Overwatch Phase

During the Overwatch phase units with Overwatch Orders get to fight before other units with Fight Orders.
All attacks during this phase are considered simultaneous and all targets are declared before any dice are rolled.

### 3.3.1. Declare Targets <!-- no toc -->

The Starting player declares targets for each of his units with Overwatch Orders.
The Second player then does the same.
Targets are declared by verbally calling them out and placing Targeting arrows in front of each attacking unit pointing towards their target.
Each unit may only target a single enemy unit.
It is important that both players are fully aware of what units are being targeted.

If a player forgets to declare a target for a unit with an Overwatch Order before dice are rolled to resolve an attack during this phase then that unit automatically targets the closest enemy unit within Range that it has Line of Sight to.

A unit may choose to delay its attack, removing its Overwatch Order and replacing it with a Fight Order instead. Should a unit have no enemy units within Line of Sight or Range then remove the Overwatch Order token.

### 3.3.2. Resolve Attacks <!-- no toc -->

The Starting player fights with all his units with Overwatch Orders against their declared targets.
Then the Second player does the same.
See the Fighting section for details on how to fight with units.
After attacking with a unit remove its Overwatch Order.
Note that casualties are not removed at this point but instead the number of casualties inflicted is marked next to the targeting arrow of the fighting unit.
Inflicted Pins are placed immediately.

### 3.3.3. Remove Casualties <!-- no toc -->

After all units with Overwatch Orders have fought it's time to remove casualties.
Starting with the Starting player, both players now remove models from their units up to the amount of casualties they suffered during the phase.
Only models that were both within Range and Line of Sight of the unit causing the casualties are eligible to be removed.
Note that Separated models are not eligible to be removed this way, they are automatically removed at the end of the Combat Phase instead.

If a unit suffered casualties from multiple units then casualties has to be removed in such a way as to maximize the number of models removed.
Should the number of available models eligible to be removed be less than the inflicted casualties then the excess is disregarded.

## 3.4. Combat Phase

During the Combat Phase units with Fight Orders get to attack.
This phase is played out identically to the Overwatch phase but it applies to all units with Fight instead of Orders.
One exception is that there's no option to choose to fight in the next phase, since there is no next phase.
Should a unit have no enemy units within Line of Sight or Range then simply remove the Fight Order token.

## 3.5. Rally Phase

The Starting player takes Rally tests for all of their units with pins tokens.
Then the Second player takes Rally tests for all of their units with pins tokens.
A Suppression Check is then done on all units with pin tokens remaining.

## 3.6. End Phase

The players now score Victory points according to the scenario being played.

# 4. Orders

Units are issued Orders at the start of the Round.

## 4.1. Advance Order <!-- no toc -->

A unit with an Advance Order may move during the Movement Phase up to its Speed.
After moving remove the Advance Order and replace it with a Fight Order.

## 4.2. Overwatch Order <!-- no toc -->

A unit with an Overwatch Order may preform a fight during the Overwatch Phase.
After fighting remove the Overwatch Order token.

## 4.3. Sprint Order <!-- no toc -->

A unit with a Sprint Order may move during the the Movement Phase up to twice its Speed.
After moving remove the Sprint Order token.

## 4.4. Move Order <!-- no toc -->

A unit with a Move Order may move during the the Movement Phase up to its Speed.
After moving remove the Move Order token.

## 4.5. Fight Order <!-- no toc -->

A unit with a Fight Order may fight in the Combat phase.
After fighting remove the Shoot Order token.

# 5. Movement

## 5.1. Moving <!-- no toc -->

When moving a unit, the controlling player moves each individual model in the unit one at a time.
Models are moved in straight lines and may change direction at any point during the move.
The sum of the lengths of the moved moved lines may not exceed the maximum distance the unit is allowed to move during the move.
There have to be sufficient space for the model during the entirety of its move.

## 5.2. Maintaining Cohesion & Separated Models <!-- no toc -->

After a unit has finished moving, check whether it is maintaining Unit Cohesion.
If Unit cohesion is not maintained then the controlling player marks the least amount of models necessary in the unit as Separated so that Unit Cohesion is restored among remaining models.
Models marked as Separated in this way may not fight and may not draw any Line of Sight during this round.

Separated models are still considered part of their unit for all rules purposes but are removed as casualties at the end of the Combat Phase.
Make sure Separated models are marked clearly; either use a special Separated marker, a Pin marker placed right on top of the model or flip the model upside down.

## 5.3. Moving Through Friendly Units <!-- no toc -->

Models may ignore models belonging to friendly units during a move as long as it has sufficient movement to clear them fully.

## 5.4. Moving Through Enemy Units <!-- no toc -->

Models may not move through enemy Unit Boundaries.

## 5.5. Moving Through Terrain <!-- no toc -->

Terrain may affect movement depending on the type of terrain, see Terrain section.

# 6. Combat

When a unit fights it goes through these steps:

1. *Nominate target enemy unit*  
This is done at the beginning of the phase for all unit.
See Declare Targets subsection in the Overwatch Phase section.
2. *Check Range & Line of Sight*  
Check which models in the fighting unit independently has both Range and Line of Sight to the target unit.
Only these are able to fight.
3. *Calculate Target Number*  
Take the units Power value and apply the relevant modifiers to it.
4. *Roll Fight Test*  
Roll a number of dice equal to the sum of Attacks characteristic the models able to fight.
Any die that is equal to or less than the Calculated Target Number is considered a success.
5. *Place Pins and mark casualties*  
Place one Pin per success on the target unit.
Some successes also inflict casualties.

## Fight Modifiers

A Fight Modifier change the Target Number when rolling a Fight Test.
There are many sources of Fight Modifiers; Special Rules and Stratagems to name a few.
The most common modifier is Cover.

## Inflicting Casualties

# 7. Morale

## 7.1. Rally Tests

When a unit takes a Rally test the controlling player rolls a number of D10s equal to the amount of pins on that unit.
The base Target Number for this roll is the Resolve of the unit.
Each successful roll removes a pin marker from the unit.

## 7.2. Suppression Check

When doing a Suppression Check on a unit compare the amount of pins on that unit with the Suppression Table.

Suppression Table:

| Pin Markers | Effect                                                      |
| :---------: | ----------------------------------------------------------- |
|     0-2     | No penalty                                                  |
|     3-5     | **Suppressed** - may only be issued a Move or a Shoot Order |
|     6+      | **Broken** - the unit is destroyed and removed from play    |

# 8. Terrain

# 9. Transports

# 10. Stratagems

- Anti-artillery radar
- Glide bomb strike
- Artillery fire mission
- Strafing run
- Remote mines

# 11. Special Rules

## 11.1. Model Rules

- Armored(Light/Medium/Heavy)
- Transport
- Tracked
- Wheeled
- Open-topped
- Tough
- Leader
- Tall
- Big Target

## 11.2. Attack Attributes

- Armor piercing
- Blast
- Ignores Cover

# 12. Scenarios

## 12.1. Battlefield Setup

## 12.2. Objectives

# 13. Force Generation
