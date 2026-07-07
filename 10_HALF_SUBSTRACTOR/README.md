Half Subtractor

RTL implementation and functional verification of a Half Subtractor using Verilog HDL.

Design
Boolean Expressions
Difference = A ^ B
Borrow     = ~A & B

Truth Table

 A  B  Difference  Borrow 
 0  0      0         0    
 0  1      1         1    
 1  0      1         0    
 1  1      0         0    

Verification

The design was verified by applying all possible input combinations through a Verilog testbench.

Simulation waveform confirms the correct generation of **Difference** and **Borrow** outputs for every input combination.

Tools

- Verilog HDL
- Icarus Verilog
- GTKWave
- Ubuntu Linux
- Git & GitHub

Learning Outcomes

- Understood the working of a Half Subtractor.
- Learned the concept of binary subtraction using combinational logic.
- Implemented the Difference output using the XOR operator.
- Implemented the Borrow output using the Boolean expression `~A & B`.
- Verified the design using a Verilog testbench and waveform analysis.
- Strengthened understanding of arithmetic circuit design in Verilog.
