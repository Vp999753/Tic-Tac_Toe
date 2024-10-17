# Tic-Tac_Toe

**Overview**

This project is a simple and interactive implementation of the classic Tic Tac Toe game. The game allows two players to compete against each other, taking turns to mark spaces in a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

**Features**

Two-Player Mode: Players can take turns to make their move.

Responsive Design: Works on both desktop and mobile devices.

Winner Detection: Automatically detects and announces the winner.

Draw Condition: Detects if the game ends in a draw.

Restart Game: Option to reset the board and start a new game.

**How to Play**

1) The game starts with an empty 3x3 grid.

2) Two players alternate turns to mark their symbol (Player 1 is "X", Player 2 is "O") in any of the 9 available cells.
3) The first player to align three of their symbols (horizontally, vertically, or diagonally) wins.
4) If all cells are filled and no player has aligned three symbols, the game results in a draw.
5) Players can restart the game by clicking the reset button.
 
 **Technologies Used**

Frontend: HTML, CSS, JavaScript (for game logic)
Optional: React.js or any frontend framework (for advanced features)

**Game Logic**

Grid System: A 3x3 grid where players click to place their marks.
Win Check: The game checks for three matching symbols in a row, column, or diagonal after every move.
Draw Condition: If all cells are filled and no winner is found, the game ends in a draw.
