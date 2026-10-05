# Week 6 Python Assignment: Safe Functions

## Files

- `safe_tools.py` - three functions (`safe_divide`, `safe_number`, `get_field`) that use try/except so they never crash.
- `README.md` - this file, describing the project and its files.

## Why can an `if` check not catch `abc` on its own?

An `if` check can only test for conditions you thought of ahead of time, and it cannot know that text like "abc" is not a valid number until `int()` actually tries to convert it and fails. A `try/except ValueError` catches that failure when it happens, so the program keeps running instead of crashing.
