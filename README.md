# Tic-tac-toe-using-c-program

## Introduction
This is a simple command-line implementation of the classic game Tic Tac Toe written in the C programming language. The game allows two players to take turns placing their marks (X or O) on a 3x3 grid until one player wins or the game ends in a draw.

## Features
- Supports two players: Player 1 (X) and Player 2 (O).
- Displays the game board after each move.
- Validates player input to ensure a valid move.
- Detects when the game ends due to a win or draw.
- Provides clear messages to indicate the winner or a draw.

## How to Run
1. Compile the source code using a C compiler. For example, using GCC:
    ```
    gcc -o tic_tac_toe tic_tac_toe.c
    ```

2. Run the compiled executable:
    ```
    ./tic_tac_toe
    ```

3. Follow the prompts to enter the row and column numbers to place your mark.

## Gameplay
- Players take turns to enter their moves by specifying the row and column numbers (1-3).
- The game board is displayed after each move to show the current state.
- The game ends when one player achieves three consecutive marks in a row, column, or diagonal, or when the board is full without a winner.

## Implementation Details
- The game logic is implemented using a 3x3 array to represent the game board.
- Functions are used to handle different aspects of the game, such as initializing the board, printing the board, checking for a win or draw, and getting player moves.
- Input validation ensures that players can only make valid moves within the bounds of the board and in empty cells.
- The game loop continues until a winner is determined or the game ends in a draw.

## Contributions
Contributions to improve the game or add new features are welcome. Feel free to fork the repository, make your changes, and submit a pull request.

This README provides an overview of the Tic Tac Toe program, how to run it, gameplay instructions, implementation details, and information on contributions and licensing. Users can refer to this document for understanding and using the program effectively.
