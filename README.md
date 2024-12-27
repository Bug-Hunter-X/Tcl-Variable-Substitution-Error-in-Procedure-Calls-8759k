# Tcl Variable Substitution Bug

This repository demonstrates a common error in Tcl programming related to variable substitution within procedure calls. The bug occurs due to improper handling of variable substitution when passing arguments to a procedure.

## Bug Description

The `badproc` procedure is defined to take a single argument and print it. However, when calling `badproc` with the variable `y`, the variable is not correctly substituted, resulting in the literal string \"$y\" being printed instead of the value of `y` (which is 10).

## Solution

The solution involves using the proper syntax for variable substitution within the procedure call, ensuring that the value of `y` is passed correctly.