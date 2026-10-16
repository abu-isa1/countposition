# Name Value Calculator

A Python command-line program that converts letters in a name into numeric values and calculates their total.

## How It Works

- Prompts the user to enter a name.
- Converts the input to uppercase.
- Assigns each letter a value from A = 1 to Z = 26.
- Adds the values together.
- Doubles the total if the input contains `%`.

## Example

For the input:

```text
ABC
```

The calculation is:

```text
A = 1
B = 2
C = 3
Total = 6
```

Output:

```text
6
```

## How to Run

**Requirement:** Python 3

Clone the repository:

```bash
git clone https://github.com/abu-isa1/countposition.git
cd countposition
```

Run the program:

```bash
python3 countposition.py
```

## Technical Concepts

- Dictionaries for mapping letters to values
- Loops for processing input
- Conditional statements
- String methods
- Accumulating a running total

## Current Limitations

The program currently expects supported characters. Inputs containing unsupported characters, such as digits or punctuation other than `%`, can cause a `KeyError`.

## Future Improvements

- Handle unsupported characters safely
- Add automated tests
- Improve input validation
- Explain the result to the user

## Technologies

- Python 3

## About

This project is part of my practical programming journey, focused on problem-solving, string processing, and building small command-line applications.
