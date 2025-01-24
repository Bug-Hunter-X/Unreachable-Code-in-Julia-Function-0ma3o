# Unreachable Code in Julia Function
This repository demonstrates an example of unreachable code in a Julia function. The issue arises due to the function's structure, where a return statement is always executed before reaching a specific code section.

## Bug Description
The `myfunction` in `bug.jl` contains a conditional statement. Regardless of the input `x`, the function will always return a value, making the `println` statement unreachable. This represents a logical error in the code that should be addressed for better code clarity and maintainability.

## Solution
The corrected function in `bugSolution.jl` removes the unreachable code to improve the code's efficiency and readability.