# Solve Sudoku with AI

## Synopsis

This code involves simple AI structures to solve a diagonal Sudoku Puzzle. A diagonal Sudoku puzzle is identical to traditional Sudoku puzzles with the added constraint that the boxes on the two main diagonals of the board must also contain the digits 1-9 in each cell (just like the rows, columns, and 3x3 blocks).

## Code Explanation

Visit http://www.cinarra.me/projects and look for the Sudoku Solver project for full explanation of the code.

## Visualization

**Note:** The `pygame` library is required to visualize your solution -- however, the `pygame` module can be troublesome to install and configure. It may not be reliable across all operating systems or versions. Please refer to the pygame documentation [here](http://www.pygame.org/download.shtml) if you need help.

Running `python solution.py` will automatically attempt to visualize your solution, but as mentioned in the explanations, you must use the provided `assign_value()` function (defined in `utils.py`) to track the puzzle solution progress for reconstruction during visuzalization.
