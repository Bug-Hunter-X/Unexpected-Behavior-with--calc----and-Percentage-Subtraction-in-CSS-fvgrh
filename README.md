# Unexpected Behavior with `calc()` and Percentage Subtraction in CSS

This repository demonstrates a common, yet subtle, bug involving the use of the `calc()` function in CSS. Specifically, when subtracting percentages within a `calc()` expression, unexpected layout can occur.

The `bug.css` file shows the problematic code.  The `bugSolution.css` provides the corrected implementation.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (or create your own HTML that links to `bug.css`) in a web browser.
3. Observe the unexpected layout.
4. Replace `bug.css` with `bugSolution.css` and see the corrected layout.

## Solution

The issue stems from how browsers handle percentage calculations within `calc()`.  The solution usually involves restructuring the CSS or using alternative units (like pixels) to avoid the percentage subtraction.