# Ada Array Indexing Error

This example showcases a potential error in Ada when an array element's value is used as an index for the same array.  If this value exceeds the array bounds, it results in a `Constraint_Error` at runtime.

The `bug.ada` file contains the erroneous code. The `bugSolution.ada` demonstrates the correction.

The error is subtle and can be easily missed, particularly in more complex code.

## How to Reproduce

1. Compile and run `bug.ada`.
2. Observe the runtime `Constraint_Error`.
3. Compile and run `bugSolution.ada` to see the corrected version.
