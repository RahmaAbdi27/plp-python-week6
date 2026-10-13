# PLP Python Week 6 Assignment

## Safe Functions

- **safe_tools.py:** Contains three functions that handle division by zero, invalid number conversion, and missing dictionary keys.
- **README.md:** Provides the assignment description and explains the use of error handling.

## Why can't an if check catch abc on its own?

An `if` statement cannot automatically catch the `ValueError` that occurs when `int("abc")` is executed. Using `try` and `except` catches the error and returns a message instead of allowing the program to crash.