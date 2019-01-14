Q1: Why is there a return address stack?

A1: Normally the return address is stored in a register called $ra. However, in this computer, the size of an instruction address is 10 bit, beyond what a register can hold. Since there is no other operations on $ra, I specifically build a stack referred as $ra and a bus connecting $ra, PC and PC buffer.
