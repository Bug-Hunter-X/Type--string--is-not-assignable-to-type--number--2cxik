# Type 'string' is not assignable to type 'number'

This repository demonstrates a common TypeScript error: 'Type 'string' is not assignable to type 'number''.  The error arises when a function expecting a number receives a string argument.  This README provides a concise explanation and a solution.

## Problem

The `add` function is designed to accept two numbers.  However, the provided example passes a string ('2') as the second argument, leading to a type error. 

## Solution

The solution involves ensuring the argument passed to the function is of the correct type.  Type checking and data validation are paramount in TypeScript for preventing these kinds of runtime errors.