#  (*2*) DeMultiplexer
## Overview

DMux.hdl is a hardware description file for the (1*2) DeMultiplexer (DMux), a fundamental digital circuit that takes a single input and delivers it to one of two possible output based on a control signal. It's implemented using simple HDL language which is specially developed for nand2tetris course. It's implements following truth table.

### Truth Table

|in |sel| a | b |   
| 0 | 0 | 0 | 0 |   
| 0 | 1 | 0 | 0 |   
| 1 | 0 | 1 | 0 |   
| 1 | 1 | 0 | 1 |


Here in is the single input and sel is the select bit that directs input to one of two possible output.


