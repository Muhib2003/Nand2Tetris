#  (2*1) Multiplexer
## Overview

Mux.hdl is a hardware description file for the (2*1) Multiplexer (MUX), a fundamental digital circuit that selects one of two input signals based on a control signal. It's implemented using simple HDL language which is specially developed for nand2tetris course. It's implements following truth table.

### Truth Table

| a | b |sel|out|   
| 0 | 0 | 0 | 0 |   
| 0 | 0 | 1 | 0 |   
| 0 | 1 | 0 | 0 |   
| 0 | 1 | 1 | 1 |   
| 1 | 0 | 0 | 1 |   
| 1 | 0 | 1 | 0 |   
| 1 | 1 | 0 | 1 |   
| 1 | 1 | 1 | 1 |

Here a and b are the two inputs and sel is the select bit that selects whether input a show in output or b.


