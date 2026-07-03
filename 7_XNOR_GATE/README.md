2-Input XNOR Gate

RTL implementation and functional verification of a 2-input XNOR gate using Verilog HDL.

Overview

This project implements a 2-input XNOR gate in Verilog HDL. The design was verified using a dedicated testbench, and the output was validated through simulation using GTKWave.

Design

Boolean Expression

Y = ~(A ^ B)

Truth Table

  A    B    Y  
  0    0    1  
  0    1    0  
  1    0    0  
  1    1    1  

Verification

The design was verified by applying all possible input combinations through a Verilog testbench.

Simulation waveform confirms the expected XNOR gate functionality.

Learning Outcomes

* Implemented a 2-input XNOR gate using the XNOR logic expression in Verilog HDL.
* Understood the relationship between XOR and XNOR operations.
* Verified the design using a dedicated Verilog testbench.
* Simulated the design using Icarus Verilog and analyzed the waveform in GTKWave.
* Strengthened understanding of combinational logic design and RTL simulation workflow.

Tools Used

* Verilog HDL
* Icarus Verilog
* GTKWave
* Ubuntu Linux
* Git & GitHub

