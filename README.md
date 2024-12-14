# Incorrect Zero Handling in foo Function

This repository demonstrates a common error in JavaScript involving the incorrect handling of zero values.

## The Bug
The `foo` function is designed to add two numbers, `a` and `b`. However, it contains a bug that causes it to return 0 if either `a` or `b` is 0. This is incorrect behavior. The function should return the sum of `a` and `b`, even if one or both of them are 0.

## The Solution
The solution involves modifying the `if` statement to correctly handle the case where either `a` or `b` is 0.  Instead of returning 0, the function should continue to add the values.