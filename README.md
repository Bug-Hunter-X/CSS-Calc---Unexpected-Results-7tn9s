# CSS Calc() Unexpected Results
This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to incorrect operator precedence or unit mismatches.

The `bug.css` file contains the problematic code, and `bugSolution.css` provides a solution.

## Bug
The original code uses `calc()` to calculate the width of an element, but the calculation is incorrect due to operator precedence issues.

## Solution
The solution clarifies the calculation by using parentheses to ensure the correct order of operations and by ensuring consistent units in the calculation. 