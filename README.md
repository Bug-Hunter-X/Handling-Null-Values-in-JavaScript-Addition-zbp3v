# Handling Null Values in JavaScript

This repository demonstrates a common error in JavaScript when dealing with null values during addition and presents an improved solution.

## Problem
The `foo` function correctly handles null inputs by returning 0. However, the explicit null checks can be cumbersome, especially with many parameters.

## Solution
The improved version utilizes the nullish coalescing operator (`??`) for a more concise and readable approach.  This operator returns the right-hand operand only if the left-hand operand is null or undefined, otherwise it uses the left operand's value.