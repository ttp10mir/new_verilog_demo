<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The project is a simple Verilog module that performs basic arithmetic operations. It uses a clock input to synchronize operations and a reset input to initialize the state. The main functionality includes adding and subtracting input signals and outputting the result.

The top module `tt_um_example` connects to various input and output signals, defined in the pinout section of `info.yaml`. The inputs are processed based on the operation mode, and the result is available on the output pins.

## How to test

To test the project, you can use a Verilog testbench that applies different input values and observes the output. Make sure to include the clock and reset signals in your testbench. You can simulate the design using a Verilog simulator like ModelSim or Verilator.

## External hardware

No external hardware is required for this project. It is a purely digital design that can be tested and simulated entirely in software.
