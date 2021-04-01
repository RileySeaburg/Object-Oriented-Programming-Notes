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
