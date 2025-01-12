# Unhandled Undefined Error in JavaScript function

This repository demonstrates a common JavaScript error: attempting to access a property of an undefined variable. The `foo` function aims to return the length of an array or 0 if the array is null. However, it fails if the input is undefined, leading to a TypeError.

The solution demonstrates how to handle undefined inputs gracefully using a short-circuit evaluation with the logical OR operator (||).