# Python - if/else, loops, functions

This project covers fundamental Python programming concepts including conditional statements, loops, and functions. The tasks progress from basic to more advanced concepts, helping to build a strong foundation in Python programming.

## Tasks

### 0. Positive anything is better than negative nothing
* A program that assigns a random signed number to the variable `number` and prints whether it's positive, negative, or zero.
* File: `0-positive_or_negative.py`

### 1. The last digit
* A program that prints the last digit of the number stored in the variable `number` along with specific messages based on the value.
* File: `1-last_digit.py`

### 2. Print alphabet
* A program that prints the ASCII alphabet in lowercase without a newline.
* File: `2-print_alphabet.py`

### 3. Print alphabet except q and e
* Similar to task 2, but skips the letters 'q' and 'e'.
* File: `3-print_alphabt.py`

### 4. Hexadecimal printing
* A program that prints numbers from 0 to 98 in both decimal and hexadecimal formats.
* File: `4-print_hexa.py`

### 5. 00...99
* A program that prints numbers from 0 to 99 with specific formatting.
* File: `5-print_comb2.py`

### 6. Print combinations of two digits
* A program that prints all possible different combinations of two digits in ascending order.
* File: `6-print_comb3.py`

### 7. islower
* A function that checks for a lowercase character.
* File: `7-islower.py`

### 8. To uppercase
* A function that prints a string in uppercase.
* File: `8-uppercase.py`

### 9. Print last digit
* A function that prints and returns the last digit of a number.
* File: `9-print_last_digit.py`

### 10. a + b
* A function that adds two integers and returns the result.
* File: `10-add.py`

### 11. a ^ b
* A function that computes a to the power of b and returns the value.
* File: `11-pow.py`

### 12. Fizz Buzz
* A classic programming challenge: print numbers from 1 to 100, but replace multiples of 3 with "Fizz", multiples of 5 with "Buzz", and multiples of both with "FizzBuzz".
* File: `12-fizzbuzz.py`

## Requirements
* All files are interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All files should end with a new line
* All code should use the pycodestyle style guide (version 2.8.*)
* All files must be executable
* The first line of all files should be exactly `#!/usr/bin/python3`

## Usage
Each file can be executed directly:
./0-positive_or_negative.py
Copy
For files containing functions, you can import and use them in your own Python scripts:

```python
islower = __import__('7-islower').islower
print("a is {}".format("lower" if islower("a") else "upper"))
