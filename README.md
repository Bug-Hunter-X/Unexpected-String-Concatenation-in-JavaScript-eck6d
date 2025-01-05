# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript bug caused by its loose typing system.  The function `foo` is intended to add two numbers, but due to the implicit type coercion, it concatenates a number and a string instead of performing arithmetic addition.

## Bug
The `bug.js` file contains the buggy code. The function `foo` takes two arguments and returns their sum. However, if one of the arguments is a string, it will perform string concatenation rather than addition.

## Solution
The `bugSolution.js` file provides a solution that explicitly checks the type of the input and handles it accordingly.  This robust approach prevents unexpected behavior caused by loose typing.

This example highlights the importance of type checking and careful consideration of implicit type coercion in JavaScript to avoid subtle but significant errors.