# CSS calc() Unexpected Behavior

This repository demonstrates an uncommon bug related to the CSS `calc()` function when combining percentages and other units. The calculated value is not what is expected, leading to layout issues.

## Bug Description

The `calc()` function produces an incorrect result when percentages are mixed with other units like pixels.  This often leads to elements not being positioned or sized as intended.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `index.html`. Observe the unexpected layout.
3. Open `bugSolution.css` to see a possible solution.

## Solution

The solution involves restructuring the CSS to avoid the problematic combination of units within `calc()`.  Different approaches might be needed depending on the specific layout needs.  See `bugSolution.css` for an example.