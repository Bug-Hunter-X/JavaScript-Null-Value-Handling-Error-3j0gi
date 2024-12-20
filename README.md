# JavaScript Null Value Handling Bug

This repository demonstrates a common error in JavaScript: improper handling of `null` values in functions. The `bug.js` file contains code that does not handle `null` inputs gracefully, leading to potential issues. The `bugSolution.js` file shows the corrected version with improved null handling.

## Bug Description

The `foo` function attempts to add two numbers. However, if either input is `null`, the function returns 0, without raising an error or providing informative feedback.

## Solution

The solution file implements better error handling. It explicitly checks for `null` values and throws a more descriptive error message if a `null` input is encountered.