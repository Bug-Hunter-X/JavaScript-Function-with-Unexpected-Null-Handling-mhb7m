# JavaScript Null Handling Bug

This repository demonstrates a common, yet subtle, error in JavaScript related to null value handling.  The `foo` function is designed to add two numbers, but it incorrectly returns `null` if either input is `null`, even if the other input is a valid number.  The solution demonstrates how to address this issue by using a more robust check for null values. 

## Bug Description

The `bug.js` file shows a function that prematurely returns `null` if any of the input values is `null`, regardless of whether other inputs are valid.  This can lead to unexpected behavior and errors. 

## Solution

The `bugSolution.js` file provides a correct implementation that addresses the problem.