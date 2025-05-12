# Register.hdl
Register.hdl is  a hdl implementation of 16-bit register. 

## Overview 

Register.hdl is a sequential logic circuit. It takes a 16 bit input and based on the load bit it returns correspond 16 bit output.

**if Load==o**

the circuit returns its current state.

**if Load==1**

then from the next cycle the circuit will returns its current input onward.
