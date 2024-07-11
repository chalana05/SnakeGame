## Snake Game

A classic Snake game implemented in Java using Swing for the GUI. Navigate the snake to eat food, grow longer, and avoid collisions to continue playing.

<b>Features</b>

• Grid-based snake movement

• Food spawns at random locations on the grid

• Score tracking

• Game over condition on collision with the snake's body or the grid boundaries

</b>Screenshots</b>
(Include some screenshots here)

<b>Getting Started</b>
<br>
<b>Prerequisites</b>

• Java Development Kit (JDK) 8 or higher

• An IDE or text editor for Java development (e.g., IntelliJ IDEA, Eclipse, VSCode)

<b>Running the Game</b>
1. Clone the repository:

        git clone https://github.com/yourusername/snake-game.git
        cd snake-game

2. Compile the Java files:

       javac SnakeGame.java App.java
 
 3. Run the game:

        java App


<b>Controls</b>

• Arrow Keys: Move the snake (Up, Down, Left, Right)

<b>Code Overview

SnakeGame.java</b>
<br>
This file contains the main logic for the Snake game. It extends JPanel and implements ActionListener and KeyListener to handle the game's rendering and control logic.

• Tile Class: Represents each segment of the snake and the food.

• SnakeGame Constructor: Initializes the game settings, including board size, snake position, and food placement.

• paintComponent: Renders the game graphics.

• move: Updates the snake's position and handles game logic for collisions and eating food.

• keyPressed: Handles user input for changing the snake's direction.

• placeFood: Randomly places food on the board.

• collision: Checks if two tiles occupy the same position.


















