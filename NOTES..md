# Python Functions and Concepts

## Introduction
This document covers fundamental Python concepts, including functions, recursion, object-oriented programming, and database queries.

## Table of Contents
- [Python Functions](#python-functions)
- [Recursion](#recursion)
- [List Comprehension](#list-comprehension)
- [Lambda Functions](#lambda-functions)
- [Modules & Import Statements](#modules--import-statements)
- [Object-Oriented Programming (OOP)](#object-oriented-programming-oop)
- [Operator Overloading](#operator-overloading)
- [Exception Handling](#exception-handling)
- [Date and Time](#date-and-time)
- [CGI & HTTP Methods](#cgi--http-methods)
- [Databases & SQL Queries](#databases--sql-queries)

---

## Python Functions

### What are Functions?
Functions are reusable blocks of code designed to perform specific tasks. They help simplify complex problems and improve code efficiency.

### Calling a Function
Functions are called using their name followed by parentheses. If parameters are required, arguments are passed inside the parentheses.

### Docstring
A docstring is a string literal serving as the first statement in a function, class, or module. It helps document the purpose of the function/class/module.

### Return Statement
Ends function execution and optionally returns a value to the caller.

### Scope and Lifetime of Variables
- **Scope**: Determines where a variable can be accessed.
- **Lifetime**: Determines how long a variable exists in memory.
- **Local Variables**: Exist only within the function they are defined in.
- **Global Variables**: Can be accessed anywhere in the program.

---

## Recursion

### What is Recursion?
Recursion is a process where a function calls itself, breaking a problem into smaller subproblems.

### Recursive Function
A recursive function requires a base case to prevent infinite recursion.

### Advantages & Disadvantages
- **Advantages**: Simplifies complex problems, improves readability.
- **Disadvantages**: Can cause excessive memory usage if recursion depth is unmanaged.

---

## List Comprehension

### What is List Comprehension?
A concise way to generate lists, applying an expression to each item in a sequence or filtering items based on a condition.

### Conditionals in List Comprehension
Conditionals allow filtering elements based on a condition, improving efficiency.

---

## Lambda Functions

### What is a Lambda Function?
A lambda function is an anonymous function that takes arguments but has only one expression.

### Use of Lambda Functions
Used in scenarios where defining a full function is unnecessary, such as in higher-order functions.

---

## Modules & Import Statements

### What is a Module?
A module is a Python file containing functions, classes, and variables that can be imported into other programs.

### Import Statements
- `import module_name`: Includes the module.
- `import module_name as alias`: Renames the module.
- `from module_name import function_name`: Imports specific functions.
- `from module_name import *`: Imports all functions (not recommended due to potential naming conflicts).

### Python Packages
A package is a directory containing multiple modules, structuring larger applications.

### Importing Modules from a Package
Modules within a package are imported using the package name followed by the module name.

---

## Object-Oriented Programming (OOP)

### OOP Concepts
Object-Oriented Programming models real-world entities using objects and classes.
- **Encapsulation**: Restricts access to attributes.
- **Inheritance**: Enables code reuse.
- **Polymorphism**: Allows objects to take multiple forms.

### Creating a Class
A class is defined using the `class` keyword, serving as a blueprint for objects.

### Instantiation
Creating an object (instance) from a class.

### Built-in Class Attributes
- `__class__`: Refers to the object's class.
- `__dict__`: Contains the object's attributes.

### Inheritance Types
- **Single Inheritance**: One class inherits from another.
- **Multiple Inheritance**: A class inherits from multiple classes.
- **Multilevel Inheritance**: A class inherits from a derived class.
- **Hierarchical Inheritance**: Multiple classes inherit from a single parent class.

### Method Overriding
Occurs when a subclass redefines a method from its superclass.

---

## Operator Overloading

### What is Operator Overloading?
Allows redefinition of operators (`+`, `-`, `==`, etc.) for objects of a class.

### Special Functions
Python provides predefined functions like `__init__`, `__str__`, and `__add__` to customize object behavior.

---

## Exception Handling

### What is Exception Handling?
Manages runtime errors using `try`, `except`, and `finally` blocks.

### Traceback
A traceback shows the sequence of function calls before an exception occurs, assisting debugging.

### Common Python Exceptions
- **TypeError**
- **ValueError**
- **IndexError**
- **KeyError**
- **FileNotFoundError**

---

## Date and Time

### DateTime Module
Provides classes for handling dates and times.

### Formatting DateTime
- `strftime()`: Formats datetime as a string.
- `strptime()`: Parses a string into a `datetime` object.

### Handling Timezones
The `pytz` library allows localization of `datetime` objects.

---

## CGI & HTTP Methods

### CGI (Common Gateway Interface)
A protocol for web servers to execute scripts (e.g., Python scripts) and generate dynamic content.

### HTTP Methods
Defines actions performed on resources:
- **GET**: Retrieve data.
- **POST**: Submit data.
- **PUT**: Update a resource.
- **DELETE**: Remove a resource.
- **HEAD**: Request metadata without fetching content.

---

## Databases & SQL Queries

### Creating a Database
Databases are created using a DBMS like MySQL or SQLite, involving table definitions and relationships.

### Executing Queries
SQL queries interact with the database:
- **SELECT**: Retrieve data.
- **INSERT**: Add data.
- **UPDATE**: Modify data.
- **DELETE**: Remove data.

---

## Conclusion
This document summarizes key Python concepts, providing a structured reference for learning and improving Python proficiency.

---