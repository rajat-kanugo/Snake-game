# Snake-game

This is a simple browser-based game of Snake implemented using HTML, CSS, and JavaScript.

How to Play
Use the arrow keys on your keyboard or swipe on a touch screen device to control the direction of the snake. 
The goal is to eat as many apples as possible without colliding with the walls or your own body. 
Each apple you eat will increase your score by one. If you collide with a wall or your own body, the game will end and your score will be displayed.

Game Mechanics
The game is played on a 100x100 grid, with each square having a size of 4 pixels.
The player controls a snake that moves continuously on the board.
The snake initially consists of one square (the head).
The player can control the direction of the snake's movement using the arrow keys or swipes (on mobile devices).
The snake grows in length by 1 square each time it eats an apple.
An apple appears at a random location on the board each time the snake eats an apple.
The game ends if the snake collides with a wall or its own tail.
The score increases by 1 each time the snake eats an apple.
The high score is saved in sessionStorage.
