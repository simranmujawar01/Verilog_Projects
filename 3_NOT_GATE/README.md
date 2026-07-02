# NOT Gate using Verilog

This is my third Verilog project. In this project, I designed a NOT gate, wrote a testbench to verify its functionality, and observed the output waveform using GTKWave.

## Files

* `not_gate.v` – NOT gate design
* `not_gate_tb.v` – Testbench
* `not_gate_waveform.png` – Output waveform
* `README.md` – Project documentation

## Truth Table

| A | Y |
| - | - |
| 0 | 1 |
| 1 | 0 |

## Simulation Commands

Compile:

```bash
iverilog -o not not_gate.v not_gate_tb.v
```

Run:

```bash
vvp not
```

View Waveform:

```bash
gtkwave not.vcd
```

## Output Waveform

![NOT Gate Waveform](not_gate_waveform.png)

## What I Learned

* Learned how to implement a NOT gate using Verilog HDL.
* Understood the use of the bitwise NOT (`~`) operator.
* Wrote a testbench for a single-input combinational circuit.
* Simulated the design using Icarus Verilog.
* Verified the output using GTKWave.
* Improved my Git and GitHub workflow by documenting and uploading the project.

