Full Adder

RTL implementation and functional verification of a Full Adder using Verilog HDL.

Design
Boolean Expressions
Sum  = A ^ B ^ Cin
Cout = (A & B) | ((A | B) & Cin)

Truth Table

 A  B  Cin  Sum  Cout
 0  0   0    0    0   
 0  0   1    1    0   
 0  1   0    1    0   
 0  1   1    0    1   
 1  0   0    1    0   
 1  0   1    0    1 
 1  1   0    0    1   
 1  1   1    1    1   

Verification

The design was verified by applying all possible input combinations through a Verilog testbench.

Simulation waveform confirms the correct generation of **Sum** and **Carry-Out (Cout)** for every possible input combination.

Tools

- Verilog HDL
- Icarus Verilog
- GTKWave
- Ubuntu Linux
- Git & GitHub

Learning Outcomes

- Understood the operation of a Full Adder.
- Learned the difference between a Half Adder and a Full Adder.
- Implemented the Sum output using the XOR operator.
- Implemented the Carry-Out logic using optimized Boolean expressions.
- Verified all eight input combinations using a Verilog testbench.
- Strengthened understanding of combinational arithmetic circuit design.
