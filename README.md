# Snake Game

A classic Snake game implemented in Java using Swing for the GUI. Navigate the snake to eat food, grow longer, and avoid collisions to continue playing.

Features

Grid-based snake movement

Food spawns at random locations on the grid

Score tracking

Game over condition on collision with the snake's body or the grid boundaries

Screenshots

Getting Started

Prerequisites

Java Development Kit (JDK) 8 or higher

An IDE or text editor for Java development (e.g., IntelliJ IDEA, Eclipse, VSCode)

Running the Game

Clone the repository

bash

Copy code

git clone https://github.com/yourusername/snake-game.git

cd snake-game

Compile the Java files



bash

Copy code

javac SnakeGame.java App.java

Run the game

bash

Copy code

java App

Controls

Arrow Keys: Move the snake (Up, Down, Left, Right)

Code Overview

SnakeGame.java

This file contains the main logic for the Snake game. It extends JPanel and implements ActionListener and KeyListener to handle the game's rendering and control logic.

Tile Class: Represents each segment of the snake and the food.

SnakeGame Constructor: Initializes the game settings, including board size, snake position, and food placement.

paintComponent: Renders the game graphics.

move: Updates the snake's position and handles game logic for collisions and eating food.

keyPressed: Handles user input for changing the snake's direction.

placeFood: Randomly places food on the board.

collision: Checks if two tiles occupy the same position.

App.java

This file contains the main method to start the game. It creates a JFrame window and adds an instance of SnakeGame to it.

Customization

You can customize the game's appearance and behavior by modifying the following variables in SnakeGame.java:

tileSize: Size of each grid tile.

boardWidth and boardHeight: Dimensions of the game board.

gameLoop timer interval: Speed of the game.



