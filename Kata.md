# String Calculator

### Core Functionality

Write a function or method which takes a calculation as a string and outputs the result.

e.g.

    calculate("1+2*3-4") = 5

There is no operator precedence - each step of the calculation is left-associative (e.g. done in order from left to right).  So the above calculation can be thought of as:

    (((1+2)*3)-4)

It's up to you which operators to implement.

### Further Requirements
    
Only natural numbers withint the integer range of your platform are allowed.

Assume the input has already been verified - you don't have to check for or handle invalid input.

### Implementation Notes

This is an open-ended problem - the intention is not to finish it, but to write the part you implement in the best way you can.

A good approach might be to start with two numbers and/or a single operator and work up from there.

If your language includes functions which do this for you (e.g. eval), you cannot use them.
