# Unexpected Calculation Results with calc() and Percentages in CSS

This repository demonstrates a common issue encountered when using the `calc()` function in CSS with percentage values.  The issue arises from the order of operations and how `calc()` handles different unit types.

## Bug Description
The `calc()` function in CSS is supposed to allow dynamic calculations of lengths. However, when combining percentages and other units, unexpected results can occur if the calculation order isn't carefully managed.  This often manifests as elements not being sized correctly or positioned as intended.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` and examine the CSS code.
3. Open `bug.html` (if provided) and view the rendered page in a web browser.  Observe the unexpected layout.

## Solution
The solution lies in properly structuring the calculation within `calc()` to ensure correct order of operations and to use compatible units.  See `bugSolution.css` for the corrected code.