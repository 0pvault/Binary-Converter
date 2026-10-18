# Binary Converter

A simple Python script that converts an 8-bit binary number into its decimal value and corresponding ASCII character.

https://github.com/0pvault/Binary-Converter

## Features

- Convert binary numbers to decimal.
- Convert decimal values to ASCII characters.
- Convert decimal values to decimal.
- Demonstrate binary place values.
- Use Python dictionaries, lists, loops, and conditionals.
- No external dependencies required.

## How It Works

The program uses binary weights (`128, 64, 32, 16, 8, 4, 2, 1`) to calculate the decimal value of an 8-bit binary number. It then uses an ASCII lookup table to retrieve the corresponding character.

## Example

**Input:**

```
binaire = "01010111"
```

**Output:**

```
Decimal:  87
ascii:  W
```

The binary number `01010111` corresponds to decimal `87`, which represents the ASCII character `W`.

## Requirements

- Python 3.x

## Usage

1. Clone or download this repository.
2. Save the code in a Python file.
3. Run the script:

```
python binary_converter.py
```

## Learning Objectives

This project explores:

- Binary-to-decimal conversion.
- ASCII character encoding.
- Binary place values.
- Basic Python programming concepts.

## Limitations

The program is designed for 8-bit binary strings and includes ASCII values from `0` to `127`. Input validation is not implemented.
