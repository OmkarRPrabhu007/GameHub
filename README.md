# GameHub
Welcome to GameHub! This repository is a collection of classic games including Sudoku Solver, Connect 4, and Tic-Tac-Toe. Each game is implemented in C++ and designed to be fun, educational, and easy to run.

--- 

## Sudoku Solver
The Sudoku Solver is a C++ program that solves Sudoku puzzles by finding a valid arrangement of numbers that satisfies the rules of the game. Sudoku is a logic-based, combinatorial number-placement puzzle. The objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contain all of the digits from 1 to 9.

### Features

- **Board Representation**: The board is represented using a 2D character array, where each element represents a cell on the board. An empty cell is represented by `.`.
- **Board Visualization**: The board is printed with different colors for initial values and the filled values. Initial values are shown in green, and filled values are shown in red.
- **Validation**: The `canFill` function checks if a number can be placed in a specific cell without violating the Sudoku rules.
- **Backtracking Algorithm**: The `Sudoku` function uses a backtracking algorithm to solve the puzzle by recursively filling empty cells with valid values and backtracking when necessary.
- **Customizable Puzzles**: The program will solve the predefined Sudoku puzzle in the code. You can modify the `board` variable in the `main` function to solve different puzzles.

--- 

## Connect 4
Connect 4 is a classic two-player game implemented in C++. The objective of the game is to connect four of one's own discs (either 'R' or 'B') vertically, horizontally, or diagonally before the opponent does.

### Features

- **Board Representation**: The board is represented using a 5x5 grid with '.' indicating empty spaces, 'R' for red player discs, and 'B' for blue player discs.
- **Board Visualization**: The board is displayed with colors indicating player moves. Red ('R') and Blue ('B') discs are highlighted in their respective colors, while empty spaces are shown in green ('.').
- **Initialization**: The `init_board` function initializes the board with empty spaces ('.').
- **Printing Board**: The `print_board` function prints the current state of the board with colors to distinguish player moves and empty spaces.
- **Player Interaction**: Players can input their moves through the console by choosing a column number where they want to drop their disc.
- **Win Condition**: The `has_won` function checks if either player has connected four discs either vertically, horizontally, or diagonally.
- **Move Calculation**: The `best_move` function uses a minimax algorithm to evaluate the game tree and choose the best move.
- **Game Loop**: The main function (`main`) controls the game flow, alternating turns between players until one player wins or the game ends in a draw.
- **Customizable Start**: Players can choose to start first or second, and they can select their character ('R' for red or 'B' for blue) at the beginning of the game.
