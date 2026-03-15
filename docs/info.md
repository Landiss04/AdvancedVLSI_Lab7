<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This design implements a 4-bit combinational multiplier with an 8-bit product output. 
The circuit receives two 4-bit operands from an 8-bit input bus, performs multiplication, and outputs the resulting 8-bit product.

## How to test

Apply an 8-bit value to ui_in where the upper 4 bits are operand A and the lower 4 bits are operand B.
Set ena = 1 so the inputs are loaded into the design.
Keep rst_n = 1 during normal operation. If rst_n = 0, both operands are cleared to zero
