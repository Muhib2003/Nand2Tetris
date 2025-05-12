# PC.hdl
PC.hdl is a hdl implementation of 16-bit program counter. 

## Overview
Program Counter is a sequential logic circuit. It takes a 16 bit input IN16, and emits a 16 bit output based on 3 control signal. These are inc, load, reset.

 **if      

    reset(t): out(t+1) = 0
    else if load(t):  out(t+1) = in(t)

    else if inc(t):   out(t+1) = out(t) + 1
    else              out(t+1) = out(t)**

Counter is a very fundamental sequential chip that works based on clock signal.