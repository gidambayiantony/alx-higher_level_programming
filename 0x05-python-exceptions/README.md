<<<<<<< HEAD
# Solution to tasks on 0x05. Python - Exceptions

## Task 0:  Safe list printing
Write a function that prints x elements of a list.

- Prototype: def safe_print_list(my_list=[], x=0):
- my_list can contain any type (integer, string, etc.)
- All elements must be printed on the same line followed by a new line.
- x represents the number of elements to print
- x can be bigger than the length of my_list
- Returns the real number of elements printed
- You have to use try: / except:
- You are not allowed to import any module
- You are not allowed to use len()

## Task 1. Safe printing of an integers list
Write a function that prints an integer with "{:d}".format().

- Prototype: def safe_print_integer(value):
- value can be any type (integer, string, etc.)
- The integer should be printed followed by a new line
- Returns True if value has been correctly printed (it means the value is an integer)
- Otherwise, returns False
- You have to use try: / except:
- You have to use "{:d}".format() to print as integer
- You are not allowed to import any module
- You are not allowed to use type()
=======
# 0x05 Python Exceptions

This project focuses on learning about exceptions and error handling in Python programming. Exception handling is a crucial aspect of programming that allows developers to manage and respond to errors that occur during the execution of their code.

## Overview

The `0x05-python-exceptions` project covers the following key topics:

- Understanding what exceptions are in Python and how they differ from syntax errors.
- Exploring different types of built-in exceptions and their purposes.
- Using `try`, `except`, `finally`, and `raise` statements for handling exceptions gracefully.
- Learning about exception propagation and how exceptions propagate through function calls.
- Using `except` statements with multiple exceptions and creating custom exceptions.

## Project Files

The project includes a variety of Python scripts demonstrating the usage of exception handling techniques, such as:

- Scripts showcasing the handling of specific exceptions like `ZeroDivisionError`, `IndexError`, `TypeError`, etc.
- Examples demonstrating the use of `try-except` blocks in various scenarios.
- Implementations illustrating the use of `finally` blocks for cleanup actions.
- Scripts featuring the raising of custom exceptions for specific cases.

## Usage

To run the Python scripts within this project, simply execute them using a Python interpreter. For example:

```bash
python script_name.py
>>>>>>> c5ab659e89e1381c38beff064c7a9fdeef0e0154
