Full Subtractor

RTL implementation and functional verification of a Full Subtractor using Verilog HDL.

Design
Boolean Expressions
Difference = A ^ B ^ Bin
Borrow = (~A & B) | (~A & Bin) | (B & Bin)

Truth Table

 A  B  Bin  Difference  Borrow
 0  0   0       0         0    
 0  0   1       1         1    
 0  1   0       1         1    
 0  1   1       0         1    
 1  0   0       1         0    
 1  0   1       0         0    
 1  1   0       0         0    
 1  1   1       1         1    

Verification

The design was verified by applying all possible input combinations through a Verilog testbench.

Simulation waveform confirms the correct generation of **Difference** and **Borrow** outputs for every possible input combination.

Tools

- Verilog HDL
- Icarus Verilog
- GTKWave
- Ubuntu Linux
- Git & GitHub

Learning Outcomes

- Understood the operation of a Full Subtractor.
- Learned the role of the Borrow-In (`Bin`) signal in binary subtraction.
- Implemented the Difference output using the XOR operator.
- Implemented the Borrow output using the optimized Boolean expression.
- Verified all eight input combinations using a Verilog testbench.
- Strengthened understanding of combinational arithmetic circuit design.
