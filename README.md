# PHP Silent Error: Non-existent function or variable

This repository demonstrates a common yet subtle issue in PHP: errors caused by misspelled function names or undefined variables that may not produce clear error messages.  The code runs without throwing obvious errors, but the results are incorrect.

The `bug.php` file contains the problematic code.  `bugSolution.php` shows how to improve the code with better error handling and type checking.

## How to Reproduce

1. Clone this repository.
2. Run `bug.php` using a PHP interpreter.
3. Observe the unexpected output.
4. Compare the output to the expected results (documented in `bugSolution.php`).

## Solution

The solution involves using stricter error reporting (in the `php.ini` file or at runtime) and adding checks to verify that functions and variables exist before using them.

This example highlights the importance of thorough testing and robust error handling in PHP applications.