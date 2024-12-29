# Unhandled Exception in TypeScript Division Function

This repository demonstrates a common error in TypeScript: unhandled exceptions. The `divide` function correctly throws an error when dividing by zero, but the main program doesn't handle this potential error.  This can lead to unexpected program crashes.

The `bug.ts` file shows the buggy code.  The `bugSolution.ts` file demonstrates a solution using `try...catch` to gracefully handle the exception.

## How to Run

1. Clone this repository.
2. Run `tsc bug.ts` to compile the buggy code.
3. Run `node bug.js` to see the exception being thrown.
4. Repeat steps 2 and 3 with `bugSolution.ts` and `bugSolution.js` to see the corrected, exception-handled version. 