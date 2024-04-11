# N Queens

## Description
The N queens puzzle is the challenge of placing N non-attacking queens on an N×N chessboard. This program solves the N queens problem.

## Usage
```
nqueens N
```

- If the user called the program with the wrong number of arguments, it prints "Usage: nqueens N", followed by a new line, and exits with the status 1.
- N must be an integer greater than or equal to 4.
- If N is not an integer, it prints "N must be a number", followed by a new line, and exits with the status 1.
- If N is smaller than 4, it prints "N must be at least 4", followed by a new line, and exits with the status 1.
- The program prints every possible solution to the problem.
- One solution per line.
- The format of the solution is as follows:
  - Each line represents a solution.
  - Each solution is represented by a list of coordinates, where each coordinate is represented by a list containing the row and column of a queen placement.
- The solutions are not printed in a specific order.

## Example
```
julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 4
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]
julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 6
[[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
[[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
[[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
[[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
julien@ubuntu:~/0x08. N Queens$ 
```

## Requirements
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3.
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/python3`.
- Your code should use the PEP 8 style (version 1.7.*).
- All files must be executable.
