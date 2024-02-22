# Tic-Tac-Toe Game

## Overview
This C++ program implements a Tic-Tac-Toe game where players can play against each other or against the computer. The game provides a simple command-line interface and allows players to take turns making moves on a 3x3 grid. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game. If all spaces on the board are filled without a winner, the game ends in a draw.

## Features
- **Player vs Computer**: One player can play against the computer, where the computer's moves are determined randomly.
- **Player X vs Player O**: Two players can play against each other, taking turns to make moves.
- **Dynamic Board Display**: The current state of the board is displayed after each move, allowing players to visualize the game progress.
- **Game State Checking**: The program checks the game state after each move to determine if a player has won or if the game has ended in a draw.

## How the Code Works

The code is structured into several functions, each responsible for a specific aspect of the game:

- **displayBoard**: This function displays the current state of the Tic-Tac-Toe board.
- **playerMoveX**: This function allows Player X to make a move on the board.
- **playerMoveO**: This function allows Player O to make a move on the board.
- **computerMove**: This function determines the computer's move when playing against the computer.
- **resetBoard**: This function resets the game board to its initial state.
- **checkGameState**: This function checks the current state of the game to determine if there is a winner or if the game has ended in a draw.
- **playAgainstComputer**: This function implements the game logic for playing against the computer.
- **playAgainstPlayer**: This function implements the game logic for playing against another player.

The `main` function serves as the entry point of the program, where the user chooses the game mode (Player vs Computer or Player X vs Player O) and the corresponding game function is called to start the game.

## How to Use
1. **Compile the Program**: Compile the C++ source code (`tic_tac_toe.cpp`) using a C++ compiler.
    ```
    g++ tic_tac_toe.cpp -o tic_tac_toe
    ```
2. **Run the Program**: Execute the compiled binary to start the Tic-Tac-Toe game.
    ```
    ./tic_tac_toe
    ```
3. **Choose Game Mode**: Select the game mode:
    - Player vs Computer (1)
    - Player X vs Player O (2)
4. **Make Moves**: Follow the prompts to enter positions (1-9) to make moves on the board.
5. **Game Outcome**: The game ends when a player wins or when the game ends in a draw. The winner or draw result is displayed.

## Contributors
- [Taha Rahman](https://github.com/TahaRahman1)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

