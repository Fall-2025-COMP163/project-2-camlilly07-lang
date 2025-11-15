Game Concept:
This project simulates a character-based battle system using object-oriented programming principles. Players can choose from three distinct classes—Warrior, Mage, and Rogue—each with unique stats and special abilities. The goal is to demonstrate inheritance, polymorphism, method overriding, and composition through interactive combat scenarios.

Design choices:
- Inheritance Hierarchy:
- Character is the base class for all entities.
- Player extends Character and introduces RPG-specific attributes like level and experience.
- Warrior, Mage, and Rogue inherit from Player, each customizing behavior and stats.
- Polymorphism:
- All character classes override the attack() method to reflect class-specific combat styles.
- Special Abilities:
- Each subclass includes a unique method (power_strike, fireball, sneak_attack) to showcase extended functionality.
- Composition:
- A separate Weapon class demonstrates composition, allowing characters to possess weapons with damage bonuses.
- Battle System:
- The provided SimpleBattle class enables one-on-one combat simulations without modifying core logic.

Creativity:
- Special abilities add depth and strategy to combat.

Ai usage:
- AI assisted with:
- Structuring the inheritance hierarchy.
- Implementing and refining method overriding.
- Debugging the Rogue’s critical hit logic.
- Adding super() calls for constructor chaining.

How to run:
- Ensure you have Python 3 installed.
- Save the code in a file named character_showcase.py.
- Open a terminal and navigate to the file location.
- Run the program using:
- python character_showcase.py



