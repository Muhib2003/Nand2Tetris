# Overview

RAM8 is a memory unit in the Nand2Tetris hardware platform. It consists of 8 registers (each of 16-bit wide), allowing storage of 8 words of 16 bits each. It is designed using Register chips and a combination of multiplexers and demultiplexers to control read and write operations.

## Read Operation:
Whether there are 8 registers (chunks of memory), but only one register is active at a time — the one pointed to by the 3-bit address.

TO read:
set address yo i;

Output: emits the state of register i;
## Write Operation:
set address: i;
set input = v;
set load = 1;
Result: the state of register i becomes v , from the next cycle onwards it emits v;

### Implementation Details:
Registers: I  used 8 Register chips as memory cells.

Demux: A DMux8Way is used to send the load signal to only one register based on the address.

Mux: A Mux8Way16 is used to select the output of the correct register to be sent to out.
