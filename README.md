# TIC-TAC-TOE-Game
A simple console-based Tic-Tac-Toe game implemented in C++ where a player competes against the computer.

## Features
- **Single Player:** Play against a computer with a random move generator.
- **Interactive UI:** Console-based interface with clear instructions.
- **Game Mechanics:** Includes win detection and tie conditions.
- **Modular Code:** Clean and reusable code structure.

## How to Play
1. Run the program.
2. Follow the prompt to place your marker (`X`).
3. The computer will automatically place its marker (`O`).
4. The game continues until someone wins or the board is full (tie).

## Code Structure
- `drawBoard(char *spaces)`: Displays the current game board.
- `playerMove(char *spaces, char player)`: Handles player's move input.
- `computerMove(char *spaces, char computer)`: Handles the computer's move using random generation.
- `checkWinner(char *spaces, char player, char computer)`: Checks for a winning condition.
- `checkTie(char *spaces)`: Checks if the game ends in a tie.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/atul2oct/TIC-TAC-TOE-Game.git

2. Navigate to the project directory:
    ```bash
    cd TIC-TAC-TOE-Game
3. Compile the program using a C++ compiler:
    ```bash
    g++ -o TicTacToe TicTacToe.cpp
     |     |     
  X  |  O  |     
_____|_____|_____
     |     |     
     |  X  |     
_____|_____|_____
     |     |     
  O  |     |  O  
     |     |     


