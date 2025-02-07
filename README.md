# Unexpected Behavior with Null and Negative Values

This repository demonstrates a common JavaScript bug involving unexpected behavior with null and negative values in conditional statements.  The `foo` function is designed to handle various input scenarios, but it exhibits issues when dealing with null and negative numbers.

## Bug Description
The `foo` function is expected to return 0 if the input is null, -1 if the input is negative, and x+1 otherwise. However, the implementation does not consistently adhere to this specification.  This leads to incorrect results under certain circumstances.

## Solution
The solution addresses the issue by explicitly checking for null before other conditions and improving the handling of negative numbers.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a text editor.
3. Run `bug.js` to see the bug in action.
4. Run `bugSolution.js` to observe the corrected behavior.