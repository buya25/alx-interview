# Minimum Operations

## Problem Description
In a text file, there is a single character H. Your text editor can execute only two operations in this file: Copy All and Paste. Given a number `n`, write a method that calculates the fewest number of operations needed to result in exactly `n` H characters in the file.

### Prototype
```python
def minOperations(n):
    pass
```

### Returns
- An integer representing the fewest number of operations needed.
- If `n` is impossible to achieve, return `0`.

### Example
```python
n = 9

# H => Copy All => Paste => HH => Paste =>HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

# Number of operations: 6

minOperations(9)  # Output: 6
```

## Concepts Needed
### 1. Dynamic Programming:
Familiarity with dynamic programming can help in breaking down the problem into simpler subproblems and building up the solution. [Dynamic Programming (GeeksforGeeks)](https://www.geeksforgeeks.org/dynamic-programming/)

### 2. Prime Factorization:
Understanding how to perform prime factorization is crucial since the problem can be reduced to finding the sum of the prime factors of the target number `n`. [Prime Factorization (Khan Academy)](https://www.khanacademy.org/computing/computer-science/cryptography/comp-number-theory/a/prime-factorization)

### 3. Code Optimization:
Knowing how to approach problems from an optimization perspective can be useful in finding the most efficient solution. [How to optimize Python code](https://stackabuse.com/how-to-optimize-your-python-code/)

### 4. Greedy Algorithms:
The problem can also be approached with greedy algorithms, choosing the best option at each step. [Greedy Algorithms (GeeksforGeeks)](https://www.geeksforgeeks.org/greedy-algorithms/)

### 5. Basic Python Programming:
Proficiency in Python, including loops, conditionals, and functions, is necessary to implement the solution. [Python Functions (Python Official Documentation)](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

## Additional Resources
- Mock Technical Interview

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should be documented
- Your code should use the PEP 8 style (version 1.7.x)
- All your files must be executable
