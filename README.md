# Incorrect Calculation in Recursive GCD Function

This repository contains a JavaScript function that attempts to calculate the greatest common divisor (GCD) of two numbers using recursion. However, the function contains a bug that leads to incorrect results in some cases.

## Bug Description

The `foo` function, designed to recursively compute the GCD using Euclid's algorithm, does not handle the case where one or both of the input numbers are 0 correctly.

## Bug Solution

The solution addresses the case where either of the inputs is 0. It returns 0 when either input is 0, and it handles the case where both inputs are 0 separately to avoid infinite recursion.