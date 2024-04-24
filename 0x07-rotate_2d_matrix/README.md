# Rotate 2D Matrix

## Project Overview
This project focuses on implementing a function to rotate a 2D matrix 90 degrees clockwise in-place. The function takes an n x n 2D matrix as input and rotates it without returning anything, directly modifying the input matrix.

## Functionality
The provided prototype for the function is as follows:
```python
def rotate_2d_matrix(matrix):
    """Rotate a 2D matrix 90 degrees clockwise."""
```

## Usage
To use the function, simply import it into your Python script and call it with a 2D matrix as the argument. Here's a sample usage:

```python
from rotate_2d_matrix import rotate_2d_matrix

if __name__ == "__main__":
    matrix = [[1, 2, 3],
              [4, 5, 6],
              [7, 8, 9]]

    rotate_2d_matrix(matrix)
    print(matrix)
```

The output will be the rotated matrix:
```
[[7, 4, 1],
 [8, 5, 2],
 [9, 6, 3]]
```

## Project Structure
The project is organized as follows:
- **GitHub repository**: [alx-interview](https://github.com/username/alx-interview)
- **Directory**: 0x07-rotate_2d_matrix
- **File**: 0-rotate_2d_matrix.py

## Contributors
- [Yabs Mullo](https://github.com/buya25)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
