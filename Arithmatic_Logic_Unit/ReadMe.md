# ALU.HDL
It's a hdl implementations of arithmatic logic unit. As a part of (nand2tetris) course.

## Overview

The ALU is a key component in any computer system, responsible for performing arithmetic and logic operations. This Hack  ALU (used in nand2tetris) computes results based on control bits and two 16-bit inputs.

 ### Functionality

The ALU takes in:

Two 16-bit inputs: x and y

**Six control bits:**

zx: zero the x input

nx: negate the x input

zy: zero the y input

ny: negate the y input

f: function code (1 = add, 0 = and)

no: negate the output

**It outputs:**

out: the 16-bit result

zr: true if out is zero

ng: true if out is negative