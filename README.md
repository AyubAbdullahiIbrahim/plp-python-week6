# PLP Python Week 6 Assignment

## Assignment Title

**Error Handling and Debugging**

This assignment practices using `try` and `except` to catch errors, handle invalid input, and keep Python programs from crashing.

## Files

### `safe_tools.py`

Contains three safe functions: `safe_divide`, `safe_number`, and `get_field`. Each function handles a specific error and returns a helpful message instead of crashing.

### `unbreakable.py`

Demonstrates how `try` and `except` can handle invalid user input and keep the program running.

### `README.md`

Provides information about the assignment, the project files, and why `try/except` is needed when handling invalid input.

## Why can the `if` check not catch `abc` on its own?

An `if` check cannot catch `abc` by itself because converting `"abc"` to an integer with `int()` raises a `ValueError`. The `try/except` block is needed to catch that exception and handle it safely.

## Expected Output

```text
5.0
Cannot divide by zero
42
Not a number
82
Field not found
```

## Concepts Practiced

* `try`
* `except`
* `ZeroDivisionError`
* `ValueError`
* `KeyError`
* Functions
* Dictionaries
* User input
* Error handling
