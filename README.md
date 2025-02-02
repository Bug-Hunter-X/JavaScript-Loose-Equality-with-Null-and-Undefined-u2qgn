# JavaScript Loose Equality with Null and Undefined

This repository demonstrates a common JavaScript error related to loose equality (==) when dealing with null or undefined values in arithmetic operations.  The `bug.js` file shows the issue, while `bugSolution.js` provides a solution.

## Problem
Loose equality (==) in JavaScript can have unexpected behavior when comparing null or undefined to numbers.  This leads to type coercion that might not produce the intended results.

## Solution
Explicitly checking for null and undefined values before performing arithmetic operations ensures that the code handles these cases gracefully and prevents unexpected behavior.