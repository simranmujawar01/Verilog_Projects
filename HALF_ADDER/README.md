Half Adder

RTL implementation and functional verification of a Half Adder using Verilog HDL.

Design
Boolean Expressions

Sum   = A ^ B
Carry = A & B

Truth Table

 A  B  Sum  Carry 
 0  0   0     0   
 0  1   1     0   
 1  0   1     0   
 1  1   0     1   

Verification

The design was verified by applying all possible input combinations through a Verilog testbench.

Simulation waveform confirms the correct generation of **Sum** and **Carry** outputs for every input combination.

Tools

- Verilog HDL
- Icarus Verilog
- GTKWave
- Ubuntu Linux
- Git & GitHub

Learning Outcomes

- Understood the working of a Half Adder.
- Learned how arithmetic circuits are built using basic logic gates.
- Implemented Sum using the XOR operator.
- Implemented Carry using the AND operator.
- Gained hands-on experience in writing and simulating combinational Verilog modules.
- Verified the design using a testbench and waveform analysis.
