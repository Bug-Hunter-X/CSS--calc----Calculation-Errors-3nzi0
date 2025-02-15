# CSS `calc()` Calculation Errors

This repository demonstrates a common error related to the `calc()` function in CSS.  The `calc()` function is powerful, but it can lead to unexpected results if not used correctly.  The example shows a scenario where the parent element's width is undefined. 

## Bug:
The `bug.css` file contains code that attempts to calculate a width using `calc()`, but it does not account for a situation where the parent width is not explicitly set, leading to inconsistent layout behavior.

## Solution:
The `bugSolution.css` file demonstrates how to solve the issue by ensuring the parent element has a defined width, or by using a more robust approach to calculate the width that handles undefined parent widths.