# Game
**Scenario Description**

**Characters:** Goblins and Orcs, both capable of dealing damage.

1. Goblins have 10 health points and can deal 2 damage points at a time

2. Orcs have 6 health points and can deal 3 damage points at a time.

**Structures:** Buildings that can take damage. Buildings have 15 health points 
and can deal no damage. 

**Objective:**

**Main Goal:** 

Implement Rust traits to manage interactions such as dealing and receiving damage.

Develop a function to simulate combats between characters or between a character and a building, demonstrating the use of traits for polymorphic behavior.

**Tasks and Enhancements**

1. Random Fight Generator:

Develop a function that randomly selects an attacker and a defender from a pool of characters and structures. This function should facilitate random combat scenarios, testing the versatility of trait implementations.

2. Create a New Character:

Introduce a new character type, with specific health and damage attributes. This task encourages extending the existing trait system to accommodate additional character types.

3. Introduce a New Trait – Recover:

Add a Recover trait that allows characters to regain health after each round of combat. This trait should define a method recover_health that increments the health points of the characters implementing it, providing a dynamic change in the game's strategy.