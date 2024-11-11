Snake Game

A classic Snake game built using Python and the Turtle graphics library. The objective is to guide the snake to eat food, grow longer, and avoid colliding with walls or itself.

Features
Score tracking: Keeps track of the current score and high score.
Snake movement: Controlled using the arrow keys.
Collision detection: Detects collisions with food, walls, and the snake’s own body.
High score: Saves and loads the high score from a data.txt file.
Requirements
Python 3.x
The turtle module (pre-installed with Python)
How to Play
Control the snake using the arrow keys:
Up arrow: Move up
Down arrow: Move down
Left arrow: Move left
Right arrow: Move right
The snake eats food (blue circle) to grow longer.
Avoid colliding with the walls or the snake’s own body.
The score increases each time the snake eats food.
The high score is saved and displayed after each game.
Game Overview
The snake starts with a length of three segments and grows each time it eats food.
If the snake collides with the walls or its own body, the game resets, and the score is saved if it exceeds the previous high score.
The game continues until the player quits


File Structure
main.py: The main game file, where the game loop and user input handling occur.
snake.py: Contains the Snake class, responsible for creating the snake, movement, and collision detection.
food.py: Contains the Food class, responsible for creating and refreshing the food at random positions.
scoreboard.py: Contains the Scoreboard class, which manages the score and high score.
data.txt: Stores the high score between game sessions.
