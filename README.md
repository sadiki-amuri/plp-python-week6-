# PLP Python Week 6 Assignment: Safe Functions and Exception Handling

This repository implements defensive exception blocks to trap structural type runtime errors cleanly without execution crashes.

## File Descriptions
* **`safe_tools.py`**: A module compiling arithmetic, data type casting, and dictionary key lookups wrapped within error handling blocks.

## Assignment Question Response
An ordinary `if` condition checking logic structure cannot cleanly catch a string like `"abc"` prior to parsing because Python strings contain variable collections of alphanumeric characters. An explicit string structure evaluation (like checking if all characters are numbers) fails to account for more complex mathematical formatting artifacts such as negative signs, decimal spaces, or structural padding, whereas a `try / except` block cleanly catches structural conversion failures dynamically at runtime regardless of the format.
