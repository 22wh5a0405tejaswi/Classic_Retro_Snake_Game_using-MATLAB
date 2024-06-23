# Classic_Retro_Snake_Game_using-MATLAB
Intro:

The classic retro Snake game is a simple, yet highly addictive video game that originated in the late 1970s and gained immense popularity on early mobile phones in the late 1990.We created the same game with small twist i.e; using MATLAB software.
Overview

The Snake game involves navigating a snake to eat food, causing it to grow longer. The objective is to score points by consuming as much food as possible without colliding with the snake's own body or the walls (if any are present).

Function Details:
* Initialization (init): This sets up the main game window, menus, and the initial game state, including the snake's starting position, the maze layout, and other parameters like level and sound settings.
  
* Controls: The snake is controlled using the arrow keys:

Left arrow (28)

Right arrow (29)

Up arrow (30)

Down arrow (31)

Additionally, the game can be paused with 'p' or spacebar.


Game Menu Options:
* File Menu: Contains options to start a new game, pause, and exit.

* Level Menu: Allows the player to select the difficulty level, which affects the snake's speed and the points awarded.

* Mazes Menu: Offers different maze configurations such as "No maze", "Box", "Tunnel", "Spiral", "Blockade", and "Twisted".

* Help Menu: Provides help, shows the score, toggles sound, and displays about information.


Gameplay Functions:
* New Game: Resets the game state, initializes the snake, and starts the game.

* Start: Runs the main game loop, updating the snake's position, checking for collisions, and handling food and bonus items.

* Food and Bonus: Functions to place food and bonus items on the board.

* DrawBoard: Updates the visual representation of the game board.

* Pause and Stop: Functions to pause and stop the game.


Visual Elements:

* Board: The game board is represented as a grid where the snake, food, and bonus items are displayed.

* Icons and Graphics: The function includes helper sub-functions to generate game icons and graphics for different game states like pause and game over.
