# Calculator Project

This project is a simple calculator implemented in Python. It provides basic arithmetic operations including addition, subtraction, multiplication, and division.

## Features

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts the second number from the first.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides the first number by the second, with error handling for division by zero.

## Usage

To use the calculator, you can import the functions from the `src/calculator.py` file into your Python script. Here’s an example of how to use the functions:

```python
from src.calculator import add, subtract, multiply, divide

print(add(5, 3))        # Output: 8
print(subtract(5, 3))   # Output: 2
print(multiply(5, 3))   # Output: 15
print(divide(5, 0))      # Output: Error: Division by zero
```

## Installation

To install any required dependencies, you can use the `requirements.txt` file. For now, it may be empty, but you can add any necessary libraries in the future.

## License

This project is open source and available under the MIT License.
