# asteroids_pygame
# Asteroids Pygame


## Project Overview

This project is an implementation of the classic Asteroids game using Pygame. It serves as an excellent showcase for object-oriented programming (OOP) principles in Python. The game features a player-controlled spaceship that must navigate through and destroy asteroids while avoiding collisions.

## TLDR: 

A Python implementation of the classic Asteroids game using Pygame, showcasing object-oriented programming principles through spaceship control, asteroid spawning, and collision detection.

## Learning Objectives

The primary goal of this project is to demonstrate and practice OOP concepts, including:

1. Class inheritance
2. Polymorphism
3. Encapsulation
4. Composition

By examining the code structure and implementation, you can gain insights into how these OOP principles are applied in a real-world game development scenario.

## Project Structure

The project is organized into several Python files, each responsible for different aspects of the game:

- `main.py`: The entry point of the game, handling the main game loop and overall logic.
- `constants.py`: Contains game constants and configuration values.
- `circleshape.py`: Defines the base `CircleShape` class, which other game objects inherit from.
- `player.py`: Implements the `Player` class, representing the player's spaceship.
- `asteroid.py`: Defines the `Asteroid` class for individual asteroids.
- `asteroidfield.py`: Manages the `AsteroidField` class, responsible for spawning and managing asteroids.
- `shot.py`: Implements the `Shot` class for the player's projectiles.

## Key OOP Concepts Demonstrated

### Inheritance

The project showcases inheritance through the `CircleShape` base class:


Both `Player`, `Asteroid`, and `Shot` classes inherit from `CircleShape`, demonstrating how common properties and methods can be shared among different game objects.

### Polymorphism

Polymorphism is evident in the way different game objects implement their own `draw` and `update` methods:


This approach allows for flexible management of game objects and their interactions.


Each class provides its own implementation of these methods, allowing for different behaviors while maintaining a common interface.

### Encapsulation

The project demonstrates encapsulation by keeping object properties and methods within their respective classes. For example, the `Player` class encapsulates all player-related functionality:


### Composition

Composition is used in the main game loop, where different game objects are composed into sprite groups:


## Game Features

1. Player-controlled spaceship with rotation and movement
2. Randomly spawning asteroids
3. Shooting mechanism
4. Collision detection between player, asteroids, and shots
5. Asteroid splitting when hit by shots

## How to Run

1. Ensure you have Python and Pygame installed.
2. Clone the repository.
3. Run `python main.py` to start the game.

## Conclusion

This Asteroids game implementation serves as an excellent example of applying OOP principles in game development. By studying the code structure and interactions between different classes, you can gain valuable insights into effective object-oriented design and implementation in Python.

Feel free to explore, modify, and expand upon this project to further your understanding of OOP and game development with Pygame!