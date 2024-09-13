

This project is a turn-based strategy game built using core Object-Oriented Programming (OOP) principles in Java. It simulates a post-apocalyptic scenario where players control heroes who battle zombies, collect resources, and navigate a dynamic map. The game features several key components organized into distinct packages:

- **Engine**: The central game engine manages gameplay, ensuring that rules are followed, heroes and zombies are controlled, and the game state is updated. 
- **Characters**: Players control different types of heroes (Fighters, Medics, Explorers), each with unique attributes such as health, action points, and attack damage. Zombies are also present as enemies, with their own attributes and behavior.
- **Collectibles**: Resources like vaccines and supplies, scattered across the game map, can be collected and used strategically.
- **World**: The game map is built as a grid, with various types of cells, including character cells, collectible cells, and trap cells, each affecting gameplay differently.
- **Custom Exceptions**: A set of custom exceptions, such as `InvalidTargetException` and `MovementException`, ensures that invalid game actions are handled gracefully.

Heroes and zombies are loaded dynamically from CSV files, allowing for an easy extension of characters. The project emphasizes proper design principles, encapsulation, and modularization, making it flexible and scalable for future enhancements.
Swing and JavaFX are needed to run this project. Run the class to start the game. 

Collaborators: Youssef Elshamy, Youssef Tahoon, Omar Wageeh. 
