# Snake-Game
Description
This is a classic Snake Game implemented in Python using the tkinter library. The objective of the game is to control the snake to eat food and grow in length while avoiding collisions with the walls and the snake's own body.

Features
Real-time gameplay with smooth animations.

Score tracking.

Collision detection.

Responsive controls using the arrow keys.

Installation
Ensure you have Python installed on your machine. You can download it from python.org.

Install the tkinter library if it's not already installed. It comes pre-installed with Python, but if needed, you can use:
//sudo apt-get install python3-tk
for Linux or use the Python installer for Windows/macOS.

Running the Game
Clone the repository or download the source code.

Navigate to the directory containing the code.

Run the following command:
//python snake_game.py

How to Play
Use the arrow keys to control the direction of the snake:
Left Arrow: Move left
Right Arrow: Move right
Up Arrow: Move up
Down Arrow: Move down
The snake will continue to move in the current direction until a new direction is provided.
Eat the red food to grow in length and increase your score.
The game ends if the snake collides with the walls or its own body.

/*
Code Overview
Main Components
Game Configuration:
GAME_WIDTH: Width of the game window.
GAME_HEIGHT: Height of the game window.
SPACE_SIZE: Size of each grid space.
BODY_PARTS: Initial size of the snake.
SPEED: Speed of the snake's movement.
SNAKE_COLOR: Color of the snake.
FOOD_COLOR: Color of the food.
BACKGROUND_COLOR: Background color of the game window.
Snake Class:
Manages the snake's body, coordinates, and growth.
Food Class:
Manages the food's position and appearance.
Game Logic:
next_turn(snake, food): Handles the snake's movement and collision detection.
change_direction(new_direction): Updates the snake's direction based on user input.
check_collisions(snake): Checks for collisions with the walls and the snake's body.
game_over(): Displays the game over message and stops the game.
Future Improvements
Implement levels with increasing difficulty.
Add sound effects.
Display the highest score.
*/
