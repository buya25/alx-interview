# Island Perimeter

This project contains a Python function to calculate the perimeter of the island described in a grid.

## Task Description

The task requires implementing a function `island_perimeter(grid)` that calculates the perimeter of the island represented by a grid. Here are the specific requirements for the grid:

- The grid is a list of lists of integers.
- In the grid:
  - `0` represents water.
  - `1` represents land.
- Each cell is a square with a side length of 1.
- Cells are connected horizontally or vertically, not diagonally.
- The grid is rectangular, with its width and height not exceeding 100.
- The grid is completely surrounded by water.
- There is only one island (or nothing).
- The island doesn’t have "lakes" (water inside that isn’t connected to the water surrounding the island).

## Usage

To use the function, simply call `island_perimeter(grid)` with a valid grid as input. The function will return the perimeter of the island.

## Example

```python
grid = [
    [0, 0, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]
print(island_perimeter(grid))  # Output: 12
```

## Repository Structure

- **GitHub Repository:** [alx-interview](https://github.com/buya25/alx-interview)
- **Directory:** 0x09-island_perimeter
- **File:** 0-island_perimeter.py

## Author

This project was implemented by [YABS MULLO] as part of an interview preparation for ALX Software Engineering.
