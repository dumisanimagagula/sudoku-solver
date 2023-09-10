# Sudoku Solver

![Sudoku Solver](https://img.shields.io/badge/Python-3.6%20%7C%203.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue)

Welcome to the Sudoku Solver project! This Python application uses the pygame library to create a graphical user interface (GUI) for automatically solving Sudoku puzzles. The solver implements a backtracking algorithm that efficiently finds solutions for Sudoku puzzles of varying complexities.

## Prerequisites
Before running the project, make sure you have the pygame library installed. You can install pygame using pip:

```bash
pip install pygame
```

## How It Works
The Sudoku Solver works by allowing you to interact with the Sudoku puzzle using the GUI. Here's a step-by-step explanation of how the project operates:

1. **Initialization**: The GUI window is created using pygame, and an empty Sudoku grid is displayed.

2. **Default Sudoku Grid**: The application initializes with a default Sudoku puzzle as shown below:

```python
Default Sudoku Board
-----------------------------
grid = [
    [7, 8, 0, 4, 0, 0, 1, 2, 0],
    [6, 0, 0, 0, 7, 5, 0, 0, 9],
    [0, 0, 0, 6, 0, 1, 0, 7, 8],
    [0, 0, 7, 0, 4, 0, 2, 6, 0],
    [0, 0, 1, 0, 5, 0, 9, 3, 0],
    [9, 0, 4, 0, 6, 0, 0, 0, 5],
    [0, 7, 0, 3, 0, 0, 0, 1, 2],
    [1, 2, 0, 0, 0, 7, 4, 0, 0],
    [0, 4, 9, 2, 0, 6, 0, 0, 7]
]
```
3. **Interaction**: You can interact with the Sudoku grid using mouse clicks and keyboard inputs.

    Here are some key interactions:

    - Use the arrow keys to navigate the grid.
    - Press a number key (1-9) to input a value into the selected cell.
    - Press Enter to visualize the solution.
    - Press 'R' to reset the board to the default Sudoku puzzle.
    - Press 'D' to clear the Sudoku board.
4. **Validation**: The program validates your input in real-time. If you enter an invalid value in a cell, it will display an error message.

5. **Solution Visualization**: After inputting the values, you can press Enter to visualize the solution. The program uses a backtracking algorithm to find the correct solution incrementally.

6. **Result Display**: If a valid solution is found, the program will display a "FINISHED" message. You can then choose to reset the board or clear it for a new Sudoku puzzle.

7. **Error Handling**: If you input an incorrect value that leads to an unsolvable Sudoku, an error message will be displayed.

8. **Custom Puzzles**: You can also experiment with different Sudoku puzzles by modifying the grid variable in the source code.

## Getting Started
To get started with the Sudoku Solver, run the Python script provided in your favorite IDE or code editor. Interact with the GUI as described above to input your Sudoku puzzle and visualize the solution.

Have fun solving Sudoku puzzles with this interactive Sudoku Solver!