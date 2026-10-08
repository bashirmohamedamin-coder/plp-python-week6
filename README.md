 Safe Functions

 Files

* `safe_tools.py` - Contains three safe functions for division, converting text to numbers, and looking up dictionary fields.
* `README.md` - Provides information about the assignment and explains why an if check alone cannot catch invalid number conversion.

 Why can the if check not catch "abc" on its own?

An `if` check cannot catch `"abc"` when using `int()` because converting `"abc"` to an integer raises a `ValueError`. The `try` and `except` block catches this error and returns `"Not a number"` instead of allowing the program to crash.
