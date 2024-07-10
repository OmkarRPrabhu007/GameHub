# GameHub
Welcome to GameHub! This repository is a collection of classic games including Sudoku Solver, Connect 4, and Tic-Tac-Toe. Each game is implemented in C++ and designed to be fun, educational, and easy to run.

## Sudoku Solver
The Sudoku Solver is a C++ program that solves Sudoku puzzles by finding a valid arrangement of numbers that satisfies the rules of the game. Sudoku is a logic-based, combinatorial number-placement puzzle. The objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contain all of the digits from 1 to 9.

### Features

- **Board Representation**: The board is represented using a 2D character array, where each element represents a cell on the board. An empty cell is represented by `.`.
- **Board Visualization**: The board is printed with different colors for initial values and the filled values. Initial values are shown in green, and filled values are shown in red.
- **Validation**: The `canFill` function checks if a number can be placed in a specific cell without violating the Sudoku rules.
- **Backtracking Algorithm**: The `Sudoku` function uses a backtracking algorithm to solve the puzzle by recursively filling empty cells with valid values and backtracking when necessary.
- **Customizable Puzzles**: The program will solve the predefined Sudoku puzzle in the code. You can modify the `board` variable in the `main` function to solve different puzzles.

