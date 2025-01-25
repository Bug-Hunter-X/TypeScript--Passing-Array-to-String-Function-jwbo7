# TypeScript Bug: Array vs. String

This repository demonstrates a common error in TypeScript: passing an array to a function expecting a string. The bug is in `bug.ts`, and the solution is provided in `bugSolution.ts`.

The bug arises from type mismatch. The `greeter` function expects a string, but an array is passed. TypeScript's type system helps catch this at compile time, preventing runtime errors. The solution handles the array correctly and provides appropriate error handling.