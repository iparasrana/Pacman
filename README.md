# Pac-Man Game

## Overview
This is a basic implementation of a Pac-Man game using Java Swing and AWT. The game features a grid-based map, walls, ghosts, and collectible food. The player controls Pac-Man to collect food while avoiding collisions with ghosts.

## Features
- **Grid-Based Map**: A customizable grid map with walls, food, and ghosts.
- **Player Control**: Use arrow keys to control Pac-Man's movement.
- **Ghost AI**: Ghosts move randomly and collide with walls.
- **Game Mechanics**:
  - Pac-Man collects food to increase score.
  - Colliding with ghosts reduces lives; losing all lives ends the game.
  - Collecting all food resets the map.

## How to Play
1. Run the program in a Java IDE or compile and execute from the command line.
2. Use the arrow keys to move Pac-Man:
   - **Up**: `↑`
   - **Down**: `↓`
   - **Left**: `←`
   - **Right**: `→`
3. Collect all food while avoiding ghosts to increase your score.
4. Lose all lives to end the game.

## Key Components
### Classes
- **`PacMan`**: Main game class that handles game logic and rendering.
- **`Block`**: Represents all game objects like walls, food, ghosts, and Pac-Man.

### Game Elements
- **Pac-Man**: Controlled by the player; can move in four directions.
- **Ghosts**: Move randomly; colliding with Pac-Man reduces lives.
- **Walls**: Static obstacles; neither Pac-Man nor ghosts can pass through them.
- **Food**: Collectible items; each increases the score by 10 points.

### Controls
- **Arrow Keys**: Move Pac-Man in the desired direction.
- **Restart Game**: When the game ends, press any key to restart.

## Customization
- **Map Layout**: Modify the `tileMap` string array to change the game map.
- **Game Speed**: Adjust the `Timer` interval in the `PacMan` constructor for faster/slower gameplay.
- **Tile Size**: Change the `tileSize` variable for different grid scales.

## Setup and Execution
1. Ensure Java Development Kit (JDK) is installed.
2. Place all required assets (e.g., images for walls, Pac-Man, and ghosts) in the project directory.
3. Compile and run the `PacMan` class.

```bash
javac PacMan.java
java PacMan
