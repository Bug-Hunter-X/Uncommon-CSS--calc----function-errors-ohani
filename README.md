# Uncommon CSS `calc()` Errors

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function.  The `calc()` function is powerful, but requires careful attention to detail to avoid unexpected results.

## Bugs:

* **Missing Spaces:**  The `calc()` function requires spaces around operators (+, -, *, /).  Missing spaces can lead to unexpected results or parsing errors.
* **Unit Inconsistency:** Ensure consistent units are used throughout the calculation.  Mixing units (e.g., `px` and `%`) without proper conversion can lead to incorrect results. 
* **Incompatible Property Types**: Cannot use colors or other non-numeric properties directly in calc().

## Solutions:

The `bugSolution.css` file provides corrected versions of the code, demonstrating how to address these errors.  Remember to always double-check your `calc()` expressions for proper spacing, consistent units, and compatible property types.