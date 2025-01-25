# Unexpected Type Coercion in JavaScript

This example demonstrates a common issue in JavaScript related to type coercion with the + operator.  When using the + operator with a number and a string, JavaScript will perform string concatenation instead of numerical addition. This can lead to unexpected results and subtle bugs.

## How to Reproduce

1.  Clone this repository.
2.  Run `node bug.js`.
3.  Observe the unexpected output.