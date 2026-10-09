# Safe Functions

## Description

This project demonstrates how to use Python exception handling (`try` and `except`) to prevent a program from crashing when an error occurs.

## Functions

### 1. safe_divide(a, b)

Divides `a` by `b`. If `b` is zero, it returns `Cannot divide by zero`.

### 2. safe_number(text)

Converts text into a whole number using `int()`. If the text cannot be converted, it returns `Not a number`.

### 3. get_field(learner, key)

Retrieves a value from a dictionary using a key. If the key does not exist, it returns `Field not found`.

## How to Run

1. Open the project folder in Visual Studio Code.
2. Open the terminal.
3. Run the following command:

   `python safe_tools.py`

## Expected Output

```
5.0
Cannot divide by zero
42
Not a number
82
Field not found
```

## Concepts Learned

* Python functions
* `try` and `except`
* Exception handling
* Dictionaries and keys
* Type conversion using `int()`
* Handling `ZeroDivisionError` and `ValueError`
* Handling `KeyError`
