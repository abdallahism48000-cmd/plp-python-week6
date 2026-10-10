# PLP Python Week 6 Lab: Safe Functions & Error Handling

## Files Included
* **safe_tools.py**: Contains three robust functions (`safe_divide`, `safe_number`, and `get_field`) utilizing `try / except` blocks to catch division errors, conversion errors, and missing dictionary keys gracefully.

## Reflection
An `if` statement cannot catch errors like trying to convert the text `"abc"` into an integer on its own because the conversion function itself (`int()`) halts execution and raises a `ValueError` the moment it encounters invalid input. Using a `try / except` block allows the program to intercept that runtime exception safely instead of crashing.
