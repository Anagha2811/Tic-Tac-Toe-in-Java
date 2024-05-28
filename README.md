# Tic-Tac-Toe Game in Java

This repository contains a simple text-based Tic-Tac-Toe game implemented in Java. The game is designed for two players who take turns marking spaces on a 3x3 grid, with the goal of aligning three of their marks in a row, column, or diagonal.

 Technical Overview

- **Initialization**: The game starts by initializing a 3x3 board with empty spaces.
- **Gameplay Loop**: Players are prompted to input the row and column for their moves. The game alternates between player 'X' and player 'O'.
- **Input Validation**: The game includes checks to ensure the move is within bounds and the selected cell is not already occupied.
- **Board Display**: The `printBoard` method displays the current state of the board after each move.
- **Win Condition**: The `checkWin` method evaluates the board to determine if the current player has won by checking all rows, columns, and diagonals.

  How to Run

To play the game, compile and run the `Main` class. Follow the prompts to enter your moves, and the game will display the board state and check for winning conditions after each turn.

This project provides a basic implementation of Tic-Tac-Toe, demonstrating core game mechanics and user interaction in Java. It serves as a foundational example that can be expanded with additional features such as draw detection, AI opponents, or a graphical user interface.
