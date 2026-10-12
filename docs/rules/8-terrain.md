# Terrain

A Terrain Feature is a distinct, specified area of the Battlefield with defined effects on unit movement, Line of Sight and whether models benefit from Cover.
This area is called the footprint of the Terrain Feature.

A model is inside a Terrain Feature if any part of its base overlaps the Terrain Feature's footprint.
Note that a model does not have to have it's entire base in contact with a Terrain Feature in order to be inside it.
Also note that a model can be in contact with a Terrain Feature without being inside it.

## Terrain & Cover

There are 2 types of Cover: Soft Cover and Hard Cover.
A target model benefits from Cover against an attacking model if all possible Line of Sight from the attacking model to the target model passes through a Terrain Feature that the target model is inside.

The level of Cover granted depends on the Terrain Feature.
Note that some Terrain Features don't grant any Cover at all.

## Terrain & Line of Sight

Terrain Features are either Clear, Obscuring or Opaque:

- Clear Terrain does not obstruct Line of Sight.
- Obscuring Terrain obstructs Line of Sight drawn completely through it, but not Line of Sight drawn to or from a model inside it.
- Opaque Terrain obstructs all Line of Sight.

## Terrain & Movement

Each Unit Type considers a Terrain Feature either Open, Difficult or Impassable:

- Open Terrain does not impede movement.
- Difficult Terrain prevents units with Sprint Orders from entering and moving through it, and units with models inside Difficult Terrain may not be issued a Sprint Order.
- Impassable prevents units from entering and moving through it.

## Elevated Terrain

Models inside Elevated Terrain may draw Line of Sight through intervening Unit Boundaries.
Models drawing Line of Sight to models inside Elevated Terrain may draw Line of Sight through intervening Unit Boundaries.

## Buildings

Buildings are Terrain Features which may be occupied by Infantry units.

### Entering Buildings

A moving Infantry Unit may enter a building if each of its models *could* move in such a way that their entire base would end up fully inside the buildings footprint, ignoring the building for the duration of this hypothetical move.
Note that the hypothetical final position of a model may overlap with others of models in the same unit.
A unit entering, and thus occupying, a building simply places all of its models on top of the building.
The exact position of occupying models does not matter.

An occupying unit's Unit Boundary is replaced with the building's footprint until it leaves the building.
A unit may not enter and leave a building during the same move.

### Leaving Buildings

An occupying unit may leave its building when making a move.
When leaving a building, move each model, one at a time, as if it started its move with its base fully inside the footprint of the building, ignoring the building during the move.
The exact starting position is chosen by the controlling player and subsequent leaving models may choose the same or an overlapping starting position as any previously moved leaving models.
A unit may not leave and enter a building during the same move.


### Buildings, Effective Range & Line of Sight

Whenever an occupying unit measures Effective Range and draws Line of Sight it chooses a single point on the building footprint.
All occupying models then use this point for both Effective Range and Line of Sight.
A new point may be chosen each time a measurement is taken.

Whenever an attacking model targets an occupied building it chooses a single point on the building footprint.
If the model is within Effective Range and has Line of Sight to that point then the model is considered to be within Effective Range and have Line of Sight to all occupying models in the building.

### Buildings & Cover

A unit occupying a building benefits from its Cover level against attacks.

### Entering Occupied Buildings & Close Quarters

A unit may not enter a building occupied by a friendly unit.
A unit may enter a building occupied by an enemy unit.

Opposing units occupying the same building are considered to be within 1" of each other for the purposes of Close Quarters.
An occupying unit and a unit outside but within 1" of the building are not considered to be within 1" of each other for the purposes of Close Quarters.

### Targeting Contested Buildings

An enemy unit inside a contested building may only be targeted by the friendly unit inside the same building.

| Terrain Feature   | Cover | Line of Sight | Infantry   | Light Mot./Wpn. Teams | Vehicles   | Special  |
| ----------------- | ----- | ------------- | ---------- | ---------------------------- | ---------- | -------- |
| Forest            | Soft  | Obscuring     | Open       | Difficult                    | Impassable |          |
| Field             | Soft  | Clear         | Open       | Open                         | Difficult  |          |
| Broken Ground     | Soft  | Clear         | Open       | Difficult                    | Impassable |          |
| Hill              | No    | Obscuring     | Open       | Open                         | Open       | Elevated |
| Mud               | No    | Clear         | Difficult  | Difficult                    | Impassable |          |
| Deep Water        | No    | Clear         | Impassable | Impassable                   | Impassable |          |
| Ruins             | Hard  | Obscuring     | Open       | Difficult                    | Impassable |          |
| Trench System     | Hard  | Clear         | Open       | Difficult                    | Difficult  |          |
| Perimeter Wall    | No    | Opaque        | Impassable | Impassable                   | Impassable |          |
| Apartment Complex | Hard  | Opaque        | Impassable | Impassable                   | Impassable | Building |
