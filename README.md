# 4-bit-Pipelined-Carry-propagation-Multiplier
As the name suggests, it's a 4 bit multiplier that's built using carry propagation architecture. It's also pipelined, so after an initial setup delay of 10 clock cycles, it can calculate a new result every single cycle.

This design uses a synchronous FA as a cell. Its code can be found in the "Synchronous FA code" file.

In this VHDL implementation, I have written all the connections between the 16 FAs needed and all the delays for the inputs, outputs and carries (so that the pipeline works) manually, without -for- loops or anythign similar.
Although this is probably the "dumb" approach, it's my first time designing something like this so it will have to do for now.
I might make a more elegant design (that's also scalable, so you can have an N-bit multiplier) sometime in the future.
