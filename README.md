Safe Functions

This repository contains the Week 6 Python assignment on safe functions and exception handling.

safe_tools.py — Contains three functions that safely handle division by zero, invalid numbers, and missing dictionary fields.

README.md — Describes the assignment files and explains why an if check cannot catch abc on its own.

An if check can test a condition, but int("abc") raises a ValueError when Python tries to convert the text to a number. The try/except block is needed to catch that error and return "Not a number" instead of crashing.