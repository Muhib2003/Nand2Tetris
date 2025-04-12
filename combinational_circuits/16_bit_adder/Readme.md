# ADD16.hdl
Add16.hdl is a hdl implementation of 16 bit adder input.

## Overview

It's a combinational logic circuits to implement 16 bit binary adder. It takes two 16 bit input by performing abinary addition returns 16 bit output.It implements following Truth Table.

### Truth Table

    |        a         |        b         |       out        |
    | 0000000000000000 | 0000000000000000 | 0000000000000000 |
    | 0000000000000000 | 1111111111111111 | 1111111111111111 |
    | 1111111111111111 | 1111111111111111 | 1111111111111110 |
    | 1010101010101010 | 0101010101010101 | 1111111111111111 |
    | 0011110011000011 | 0000111111110000 | 0100110010110011 |
    | 0001001000110100 | 1001100001110110 | 1010101010101010 |


