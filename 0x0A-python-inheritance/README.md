# 0x0A. Python - Inheritance

![Python Logo](https://www.python.org/static/img/python-logo.png)

## Description

This project focuses on the concept of Inheritance in Python and Object-Oriented Programming (OOP) principles. It aims to solidify your understanding of inheritance, superclasses, subclasses, and the use of various built-in functions.

## Learning Objectives

By completing this project, you're expected to comprehend the following concepts without relying on external resources:
- Understanding why Python programming is remarkable.
- Recognizing superclass, base class, or parent class.
- Grasping the concept of subclasses.
- Listing all attributes and methods of a class or instance.
- Identifying when an instance can have new attributes.
- Implementing class inheritance.
- Defining classes with multiple base classes.
- Recognizing the default class every class inherits from.
- Overriding a method or attribute inherited from the base class.
- Understanding attributes or methods available by heritage to subclasses.
- Grasping the purpose of inheritance in programming.
- Utilizing isinstance, issubclass, type, and super built-in functions.

## Project Files and Purposes

- **0-lookup.py:** Contains a function that returns the list of available attributes and methods of an object.
- **1-my_list.py:** Implements a class `MyList` that inherits from `list`. Defines a method to print the list in sorted order.
- **2-is_same_class.py:** Defines a function to check if an object is exactly an instance of the specified class.
- **3-is_kind_of_class.py:** Implements a function that checks if an object is an instance of, or inherited from, the specified class.
- **4-inherits_from.py:** Contains a function to check if an object is an instance of a class that inherited (directly or indirectly) from the specified class.
- **5-base_geometry.py:** Defines an empty class `BaseGeometry` without any implementation.
- **6-base_geometry.py:** Enhances the `BaseGeometry` class by adding a method `area()` that raises an Exception if not implemented.
- **7-base_geometry.py:** Further extends `BaseGeometry` by including a method `integer_validator()` to validate integer values.
- **8-rectangle.py:** Implements a class `Rectangle` that inherits from `BaseGeometry`, validating width and height.
- **9-rectangle.py:** Extends `Rectangle` class by implementing the `area()` method and adjusting print and str methods for descriptive output.
- **10-square.py:** Implements a class `Square` that inherits from `Rectangle`, ensuring size is a positive integer and implementing the `area()` method.
- **11-square.py:** Extends `Square` class by modifying print and str methods for descriptive output.
