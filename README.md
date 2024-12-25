# TypeScript Type Error in Addition Function

This repository demonstrates a common type error in TypeScript: attempting to add a number and a string.  The provided code includes a function designed to add two numbers; however, when called with a string argument, it throws a type error.

The solution shows how to correctly handle this scenario by adding type checking to the function, preventing such errors at compile time.  The improved function either explicitly handles string conversion or avoids the use of strings altogether.

## How to Run

1.  Clone this repository.
2.  Navigate to the repository's directory in your terminal.
3.  Compile and run the TypeScript code using the TypeScript compiler (tsc) and Node.js (node).

   ```bash
tsc bug.ts
node bug.js

tsc bugSolution.ts
node bugSolution.js
```