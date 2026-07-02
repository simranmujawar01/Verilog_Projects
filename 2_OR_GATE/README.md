# 2-Input OR Gate

This is my second Verilog project. In this project, I designed a 2-input OR gate, wrote a testbench to verify all input combinations, and observed the output waveform using GTKWave.

## Files

* `or_gate.v` – OR gate design
* `or_gate_tb.v` – Testbench
* `or_gate_waveform.png` – Output waveform

## Truth Table

| A | B | Y |
| - | - | - |
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

## Simulation Commands

Compile:

```bash
iverilog -o or or_gate.v or_gate_tb.v
```

Run:

```bash
vvp or
```

View Waveform:

```bash
gtkwave or.vcd
```

## Output Waveform

![OR Gate Waveform](or_gate_waveform.png)

## What I Learned

* How to implement an OR gate in Verilog.
* How to write a simple testbench.
* How to simulate the design using Icarus Verilog.
* How to verify the output using GTKWave.
* How to manage the project using Git and GitHub.

