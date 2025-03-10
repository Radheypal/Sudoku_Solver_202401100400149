# Sudoku_Solver_202401100400149
# Sudoku Solver - README

## Introduction
This program is a Sudoku solver that uses the **backtracking algorithm** to solve Sudoku puzzles efficiently. The program scans the board, tries placing numbers, and backtracks if necessary to find a valid solution.

## Problem Statement
The goal is to solve a 9×9 Sudoku puzzle by filling in missing numbers while following these constraints:
- Each row must contain numbers 1 to 9 without repetition.
- Each column must contain numbers 1 to 9 without repetition.
- Each 3×3 sub-grid must contain numbers 1 to 9 without repetition.

## Features
- Solves any valid 9×9 Sudoku puzzle using **backtracking**.
- Checks for valid number placements.
- Prints the puzzle before and after solving.
- Includes predefined Sudoku puzzles for testing.

## How It Works
1. **Finding an Empty Cell** - The program looks for an empty space (denoted as `0`).
2. **Placing Numbers (1-9)** - It tries numbers 1 to 9 in the empty space.
3. **Checking Validity** - It ensures the number follows Sudoku rules.
4. **Backtracking** - If no number fits, it backtracks and tries a different number.
5. **Solution Found** - The process continues until the puzzle is completely solved.

## Files Included
- `sudoku_solver.py` - The main Sudoku solver script.
- `README.md` - This documentation file.

## How to Run
1. Install Python (if not already installed).
2. Save the program as `sudoku_solver.py`.
3. Run the script using:
   ```sh
   python sudoku_solver.py
   ```
4. The program will print the Sudoku puzzle before and after solving it.



## References
1. **Sudoku Puzzle Rules** – [www.sudoku.com](https://www.sudoku.com)
2. **Backtracking Algorithm** – Cormen et al., *Introduction to Algorithms* (MIT Press)
3. **Solving Sudoku with Algorithms** – Norvig, P. (2012), *Solving Every Sudoku Puzzle* [norvig.com](https://norvig.com/sudoku.html)

## Conclusion
This Sudoku solver effectively finds solutions using **backtracking**. It ensures valid placements and corrects mistakes recursively, demonstrating the power of algorithmic problem-solving.

