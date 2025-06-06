# Advanced_Programming_Assignment_3

## Overview

This project simulates a symbol table, a crucial data structure used in compilers to store information about identifiers (variables, functions, etc.). The implementation supports operations like inserting symbols, assigning values, managing scopes with blocks, and looking up symbols.

## Key Features

*   **List-based Implementation:** The symbol table is implemented using Python lists.
*   **Scope Management:** Supports nested scopes using `BEGIN` and `END` blocks.
*   **Symbol Operations:** Implements `INSERT`, `ASSIGN`, `LOOKUP`, `PRINT`, and `RPRINT` commands.
*   **Error Handling:** Detects and raises semantic errors like `Undeclared`, `Redeclared`, `TypeMismatch`, `UnclosedBlock`, and `UnknownBlock`.

## Files

*   `main.py`: The main program entry point.
*   `Symbol.py`: Defines the Symbol class.
*   `SymbolTable.py`: Contains the `simulate` function where you implement the symbol table logic.
*   `TestSuite.py`:  Where you write your test cases.
*   `TestUtils.py`: Utility functions for testing.
*   `README.md`: This file.

## Requirements and Constraints

*   **Allowed Modules:** You can only import `StaticError`, `Symbol`, and `functools` in `SymbolTable.py`. No other imports are allowed.
*   **Functional Programming:** You must use functional programming concepts (high-order functions, list comprehensions).  Avoid traditional loops (`for`, `while`).
*   **Immutability:**  Variables within function bodies should be assigned only once to ensure data immutability.
*   **No Global Variables or Classes:** You can only define functions using the `def` keyword. No classes or global variables allowed.

## Error Handling

The program should raise the appropriate error (using `raise`) when a semantic error is detected. The errors are:

*   `Undeclared`
*   `Redeclared`
*   `TypeMismatch`
*   `UnclosedBlock`
*   `UnknownBlock`

