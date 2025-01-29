# Brick Breaker Game

This project is a classic Brick Breaker game implemented in Java using Swing for the graphical user interface.  The player controls a paddle to bounce a ball and break all the bricks to win the game.

## Features

* **Gameplay:** Classic Brick Breaker gameplay with a paddle, ball, and a wall of bricks.
* **Score:** Tracks the player's score based on the number of bricks broken.
* **Levels:**  The game can be configured with different levels by changing the number of brick rows and columns. The current implementation uses a 3x7 grid of bricks.
* **Win Condition:** The player wins by breaking all the bricks.
* **Game Over:** The game ends if the ball falls below the paddle.
* **Restart:** The player can restart the game by pressing Enter.
* **Controls:** The player controls the paddle using the left and right arrow keys.

## Prerequisites

* **Java Development Kit (JDK):**  A compatible JDK is required to compile and run the game.

## Setup and Running

1. **Download:** Download the project files (the Java code).
2. **Compilation:** Compile the Java code. You can use a command-line compiler or an IDE like IntelliJ. If using the command line, navigate to the directory containing the `Game.java` file and compile with: `javac Game.java MapGenerator.java`.
3. **Execution:** Run the compiled code. Using the command line: `java Game`
4. **IDE:** If using an IDE, simply import the project and run the `Game` class.

## How to Play

1. **Launch the Game:** Run the compiled Java code.
2. **Control the Paddle:** Use the left and right arrow keys to move the paddle horizontally.
3. **Break Bricks:** Bounce the ball off the paddle to break the bricks.
4. **Win the Game:** Break all the bricks to win.
5. **Game Over:** Avoid letting the ball fall below the paddle.
6. **Restart:** Press Enter to restart the game after winning or losing.
