# Object Oriented Analysis Uses Cases

## Object Oriented Analysis

- Object oriented analysis focuses on the problem and the requirements. 
- Focus on what the system is supposed to do. 
- Implementation details are mostly ignored.
- An analysis model is created
    - Done through user stories or uses cases
    - Involves key abstractions from the problem domain.
    - Constraints of technologies are ignored.

- Steps
    1. Find the key objects.
    2. Describe how they interact.
    3. Define the internal behavior of each object.

### Example : Car Game (Reckless Driver)
- Objective: Keep driving as long as you can & earn money by smashing objects. Spend money on powerups.

- Smash into traffic, side objects (hydrant, phone booth, etc.)

- Each hit will damage the player car and reduce its health 
    - repair through health pickups

- Amount of damage caused is accumulated by the player 
    - Smash anything, except trees & police cars (causes instant player death)

- Powerups are available

- Heavy armour: protects player car from damage • Bomb : destroys objects in the path of the player car

#### Key Objects

- Player Car
- Traffic cars
- Fire Hydrant
- Phone booth
- Newspaper box
- Bus stand bench
- Hotdog cart
- Tree
- etc

#### Example Gameplay

- The player car smashes into traffic car
- Show sparks at point of contact
- Play crash audio
- Apply damage to player car & reduce health
- Compute damage caused to traffic car
- Accumulate damage as cash

## Use Case

- Defines a model of a system behavior.
- Uses natural language.
    - Designers and programmers use as a common reference.
- Decomposes large system specification into small manageable parts.
- Smaller parts are easily described, hence easily implemented.
- Models functional behavior of the system.

### Use Case Description

1. Goal
    - Use Case's place within the system and why it is important.
2. Preconditions
    - What is required before use case execution.
3. Successful End Condition
    - System condition after successful execution.
4. Failed End Condition
    - System condition after failed execution.
5. Primary Actors
    - Actors that may trigger the use case.
6. Secondary Actors
    - Actors that participate but are not main players in a use case's execution.
7. Trigger
    - Event that causes the use case to execute.
8. Main Flow
    - Important steps in a use case's normal execution.
9. Extensions
    - Alternative steps in use case execution.