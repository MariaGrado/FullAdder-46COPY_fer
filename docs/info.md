<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements a one-bit full adder using
combinational logic derived from Karnaugh maps.

The original circuit was designed by Levi Feldman
for Tiny Tapeout 7, project #46.

Inputs:
- ui[0]: A
- ui[1]: B
- ui[2]: Cin

Outputs:
- uo[0]: Sum
- uo[1]: Cout

## How to test

Apply the eight possible binary combinations to
inputs A, B and Cin.

Verify that the Sum and Cout outputs follow the
truth table of a one-bit full adder.

## External hardware

For physical testing, the Tiny Tapeout TT07
demonstration board can be used to apply input
signals and observe the outputs.

