# Calculator

A lightweight calculator written in Python. It allows you to operate on two numbers with basic arithmetic operations.

## Features

- Basic arithmetic operations (`+`, `-`, `*`, `/`, `**`, `%`)
- Operate on two numbers
- Simple and intuitive command-line interface
- No external dependencies &mdash; runs on standard Python

## Requirements

- Python 3.x (tested on Python 3.10+)

## Usage

1. Save the script as `calc.py` (or any name you prefer).
2. Run the script:
   ```Bash
   python calc.py # python3 on mac and linux
   ```
3. You will be prompted to enter the first number. It will then prompt you for a second number.
4. Once both numbers are entered, you will be prompted for the operation.

### Supported Operations

- `+` : Addition
- `-` : Subtraction
- `*` : Multiplication
- `/` : Division
- `%` : **Modulo** (remainder after division)  
  Note: This is *not* percentage!  
  The modulo operation returns the remainder when the first number is divided by the second.  
  Examples:
  - `10 % 3` → `1` (because 10 ÷ 3 = 3 with a remainder of 1)
  - `20 % 5` → `0` (because 20 ÷ 5 = 4 with no remainder)
- `**` : Exponentiation (power)  
  Example: `2 ** 3` → `8` (2 raised to the power of 3)

## Example Session

```text
Welcome to calc.py! Enter 'q' at any time to exit the program.

Enter first number: 5
Enter second number: 5
Enter operation (+, -, *, /): +
Result: 10.0

Enter first number: 1337
Enter second number: 0
Enter operation (+, -, *, /): /
Error: Divide by zero

Enter first number: q
Exiting program
```

Feel free to extend the script with additional features!
