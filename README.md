# Hack Bug Report: Stack Overflow in Recursive Function

This repository demonstrates a common bug in Hack: a stack overflow error caused by unbounded recursion.  The `foo` function calculates the factorial of a number recursively.  However, without proper handling for large inputs, the function leads to excessive recursive calls, exceeding the maximum call stack depth.

The `bug.hack` file contains the erroneous code. The `bugSolution.hack` file provides a corrected version that avoids the stack overflow by using iterative approach.