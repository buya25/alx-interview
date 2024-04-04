# Project: 0x04. UTF-8 Validation

## Description
This project focuses on validating whether a given dataset represents a valid UTF-8 encoding. The task involves applying knowledge of bitwise operations, understanding the UTF-8 encoding scheme, and proficiency in Python programming.

## Concepts and Resources
To effectively complete this project, the following concepts and resources will be beneficial:
- **Bitwise Operations in Python**: Understanding and utilizing operations such as AND (&), OR (|), XOR (^), NOT (~), shifts (<<, >>).
- **UTF-8 Encoding Scheme**: Familiarity with UTF-8 encoding rules, including character encoding into one or more bytes and recognizing patterns for valid UTF-8 encoded characters.
- **Data Representation**: Handling data at the byte level and working with the least significant bits (LSB) of integers to simulate byte data.
- **List Manipulation in Python**: Iterating through lists, accessing list elements, and employing list comprehensions.
- **Boolean Logic**: Applying logical operations to make decisions within the program.

## Resources
- [Python Bitwise Operators](https://docs.python.org/3/library/stdtypes.html#bitwise-operations-on-integer-types)
- [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
- [Characters, Symbols, and the Unicode Miracle](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

## Requirements
- **Editors**: Allowed editors include vi, vim, and emacs.
- **Platform**: All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python3 (version 3.4.3).
- **File Endings**: All files should end with a new line.
- **First Line**: The first line of all files should be exactly `#!/usr/bin/python3`.
- **README.md**: A README.md file at the root of the project folder is mandatory.
- **PEP 8 Style**: Code should adhere to PEP 8 style guidelines (version 1.7.x).
- **Executable Files**: All files must be executable.

## Tasks
### 0. UTF-8 Validation
Write a method that determines if a given dataset represents a valid UTF-8 encoding.

- **Prototype**: `def validUTF8(data)`
- **Return**: True if data is a valid UTF-8 encoding, else return False
- A character in UTF-8 can be 1 to 4 bytes long
- The data set can contain multiple characters
- The data will be represented by a list of integers
- Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer

## Usage
- Clone the GitHub repository: `git clone https://github.com/alx-interview`
- Navigate to the directory `0x04-utf8_validation`
- Run the main file `0-main.py` to test the implemented function.

## Example
```
$ ./0-main.py
True
True
False
```

## Files
- **0-validate_utf8.py**: Python script containing the function to validate UTF-8 encoding.
- **0-main.py**: Main file for testing the implementation.
