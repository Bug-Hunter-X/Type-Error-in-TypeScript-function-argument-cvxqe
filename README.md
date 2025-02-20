# Type Error in TypeScript Function Argument

This example demonstrates a common type error in TypeScript that occurs when a function expects a specific type of argument, but the provided argument has a different type.

## Bug

The `greeter` function is defined to accept a string argument and return a string.  However, the `user` variable is an array of strings. Calling `greeter` with `user` results in a type error because the function is trying to use an array as a string.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way `user` is used to call the function.  The solution code demonstrates how to iterate over the array and call `greeter` for each string in the array.