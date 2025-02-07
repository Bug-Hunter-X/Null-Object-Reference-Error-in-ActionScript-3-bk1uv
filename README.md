# ActionScript 3 Null Object Reference Error

This repository demonstrates a common ActionScript 3 error: attempting to access a property of an object that might be null or undefined. This leads to a `TypeError: Error #1009: Cannot access a property or method of a null object reference.` runtime error.

The `bug.as` file contains the erroneous code. The `bugSolution.as` file provides a corrected version.

## How to Reproduce

1.  Compile and run `bug.as`. Observe the runtime error.
2.  Compile and run `bugSolution.as`. Observe the correct behavior.

## Solution

Always check for `null` or `undefined` before accessing properties of an object.  Use conditional statements (e.g., `if` statements) or the nullish coalescing operator (??) to handle potential null values.