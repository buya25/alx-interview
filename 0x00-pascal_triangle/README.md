# Pascal's Triangle

Create a function `def pascal_triangle(n):` that returns a list of lists of integers representing Pascal’s triangle of `n`:

## Task Description

- Returns an empty list if `n <= 0`.
- You can assume `n` will always be an integer.

## Method Signature

```python
def pascal_triangle(n):
```

## Parameters

- `n`: An integer representing the number of rows in Pascal's triangle.

## Returns

- A list of lists of integers representing Pascal's triangle.

## Example

```python
pascal_triangle = __import__('0-pascal_triangle').pascal_triangle

def print_triangle(triangle):
    """
    Print the triangle
    """
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))

if __name__ == "__main__":
    print_triangle(pascal_triangle(5))
```

### Output

```
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
```

## Repository

- **GitHub repository:** [alx-interview](https://github.com/username/alx-interview)
- **Directory:** 0x00-pascal_triangle
- **File:** 0-pascal_triangle.py
