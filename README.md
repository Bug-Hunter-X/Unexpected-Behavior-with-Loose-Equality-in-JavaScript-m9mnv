# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (`==`). Loose equality can lead to unexpected behavior when comparing values of different types.

## The Bug
The `bug.js` file contains a function `foo` that adds two numbers. However, it uses loose equality (`==`) to check for `null` values. This can cause unexpected results.

## The Solution
The `bugSolution.js` file demonstrates the correct way to handle `null` values using strict equality (`===`). Strict equality prevents type coercion, ensuring accurate comparisons.