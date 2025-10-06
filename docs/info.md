<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Q1, QB1 are latched by FF1
Q2, QB2 are latched by FF2
AND, OR, XOR are determined by boolean functions of LOGIC1 and LOGIC2
BUFF is logically equal to LOGIC3

## How to test

Use the CLK, FF1, FF2 to test the latches
Use LOGIC1 and LOGIC2 to test the AND/OR/XOR gates
Use LOGIC3 to test the BUFF output

## External hardware

Connect a push-button to the CLK input; connect switches to LOGIC1,2,3
Connect an LED bar output to all of the eight outputs in a parallel fashion
