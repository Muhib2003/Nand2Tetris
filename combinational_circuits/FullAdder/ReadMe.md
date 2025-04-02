# FULLADDER

## Overview

FulllAdder.hdl is a combinational logic circuits to implement fulladder in hdl.
A Full Adder takes three inputs (A, B, and Carry-in) and produces two outputs:

Sum (S)--The sum of the input bits.

Carry-out (Cout)-- The carry generated from the addition.
This Arithmatic component implements following truth table.

### Truth Table

     | a | b | c |sum|carry| 
     | 0 | 0 | 0 | 0 |  0  | 
     | 0 | 0 | 1 | 1 |  0  |
     | 0 | 1 | 0 | 1 |  0  |
     | 0 | 1 | 1 | 0 |  1  |
     | 1 | 0 | 0 | 1 |  0  |
     | 1 | 0 | 1 | 0 |  1  |
     | 1 | 1 | 0 | 0 |  1  |
     | 1 | 1 | 1 | 1 |  1  |
