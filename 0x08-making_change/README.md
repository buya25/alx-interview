# Making Change

This project focuses on solving the problem of determining the fewest number of coins needed to meet a given total amount using a pile of coins with different values.

## Task Description

### Task 0: Change comes from within

Given a list of coin values and a total amount, the goal is to determine the fewest number of coins needed to meet the total. If the total cannot be met by any number of coins available, return -1.

#### Prototype
```python
def makeChange(coins, total)
```

#### Returns
- The fewest number of coins needed to meet the total.
- If the total is 0 or less, return 0.

#### Parameters
- `coins`: A list of coin values available.
- `total`: The total amount to be met.

#### Constraints
- The value of a coin will always be an integer greater than 0.
- You can assume you have an infinite number of each denomination of coin in the list.

#### Example
```python
print(makeChange([1, 2, 25], 37))  # Output: 7
print(makeChange([1256, 54, 48, 16, 102], 1453))  # Output: -1
```

## Repository Structure

- `0x08-making_change/`: Main directory containing the task.
- `0-making_change.py`: File containing the solution for the task.
- `0-main.py`: Main file for testing the solution.

## How to Run

1. Clone this repository.
2. Navigate to the `0x08-making_change` directory.
3. Run the main file `0-main.py` using Python. For example: `python3 0-main.py`

Feel free to explore the repository for more information on the task and its solution.

## Author

This repository is maintained by [Yabs Mullo].
