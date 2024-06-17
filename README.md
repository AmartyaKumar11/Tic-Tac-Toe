# Tic-Tac-Toe Game in C++

## Overview

This project is a simple implementation of the classic Tic-Tac-Toe game in C++, created as a fun way to spend my summer break. The game allows two players to take turns marking the spaces in a 3×3 grid, with the goal of placing three of their marks in a horizontal, vertical, or diagonal row.

## Features

- **Two-Player Mode**: Play against a friend in a classic Tic-Tac-Toe match.
- **Simple Console Graphics**: The game board is displayed directly in the console.
- **Input Validation**: Ensures players enter valid moves.
- **Win and Draw Detection**: Automatically detects and announces a win or a draw.

## Getting Started

### Prerequisites

To run this game, you need a C++ compiler such as `g++`.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/tic-tac-toe.git
    cd tic-tac-toe
    ```

2. **Compile the game**:
    ```bash
    g++ -o tic_tac_toe tic_tac_toe.cpp
    ```

3. **Run the game**:
    ```bash
    ./tic_tac_toe
    ```

## How to Play

1. **Start the game**: Run the compiled program.
2. **Enter player moves**: Players take turns to enter their moves. Player X starts first.
3. **Input format**: Enter the row and column numbers (0, 1, or 2) to place your mark.
4. **Win or draw**: The game announces if a player wins or if it's a draw.

## Game Rules

- The game is played on a grid that's 3 squares by 3 squares.
- Player 1 is 'X' and Player 2 is 'O'. Players take turns putting their marks in empty squares.
- The first player to get 3 of their marks in a row (up, down, across, or diagonally) is the winner.
- If all 9 squares are full and no player has 3 marks in a row, the game is a draw.

## Example Gameplay

```
Welcome to my summer project: Tic-Tac-Toe!
A fun creation to keep me busy during the break.

-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
Player X, enter row (0-2) and column (0-2): 0 0

-------------
| X |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
Player O, enter row (0-2) and column (0-2): 1 1

-------------
| X |   |   | 
-------------
|   | O |   | 
-------------
|   |   |   | 
-------------
...
```

## Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

## Acknowledgements

Thanks to everyone who takes a moment to check out this project. It was a great way to stay sharp and have fun over the summer!

---

Enjoy playing, and happy coding!

