# Week 6 Assignment – Safe Functions and Exception Handling

## Project Description

This project demonstrates Python exception handling using `try` and `except` to prevent programs from crashing when errors occur.

## Files

- **safe_tools.py:** Contains three safe functions for division, number conversion, and dictionary field lookup.
- **README.md:** Provides information about the assignment and explains the use of exception handling.

## Why can the if check not catch "abc" on its own?

An `if` statement can check conditions, but it cannot directly catch a `ValueError` raised when converting invalid text such as "abc" into an integer. The `try` and `except` statements handle this error and allow the program to continue running.
