# Sudoku_solver

#Description

The Sudoku Solver is a C++ program designed to solve Sudoku puzzles. It uses a backtracking algorithm to fill in the empty cells of a 9x9 Sudoku grid, ensuring the solution adheres to the rules of Sudoku:

Each row must contain the numbers 1-9 without repetition.

Each column must contain the numbers 1-9 without repetition.

Each 3x3 sub-grid must contain the numbers 1-9 without repetition.

#Features

Backtracking Algorithm: Efficiently solves any valid 9x9 Sudoku puzzle.

Dynamic Input: Handles puzzles with varying numbers of pre-filled cells.

Validation: Ensures that the solution respects all Sudoku rules.

#How to Run

Prerequisites

A C++ compiler (e.g., g++ from GCC).

A terminal or command-line environment.

#Compilation

Use the following command to compile the program:

g++ -o sudoku_solver sudoku_solver.cpp

#Execution

Run the compiled program with:

./sudoku_solver

Input Format

The Sudoku grid is predefined in the source code as a 2D array. You can modify the grid in the main function:

int grid[N][N] = {
    {5, 3, 0, 0, 7, 0, 0, 0, 0},
    {6, 0, 0, 1, 9, 5, 0, 0, 0},
    {0, 9, 8, 0, 0, 0, 0, 6, 0},
    {8, 0, 0, 0, 6, 0, 0, 0, 3},
    {4, 0, 0, 8, 0, 3, 0, 0, 1},
    {7, 0, 0, 0, 2, 0, 0, 0, 6},
    {0, 6, 0, 0, 0, 0, 2, 8, 0},
    {0, 0, 0, 4, 1, 9, 0, 0, 5},
    {0, 0, 0, 0, 8, 0, 0, 7, 9}
};

Output

The program will print the solved Sudoku grid to the terminal:

5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9

If no solution exists, it will output:

No solution exists

Contribution

Contributions are welcome! You can:

Add functionality for dynamically inputting puzzles.

Optimize the backtracking algorithm.

Develop a graphical user interface (GUI) for better user interaction.
