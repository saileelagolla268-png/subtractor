# Verilog Full Subtractor

## Description
This project implements a **1-bit Full Subtractor** in Verilog HDL.

### Inputs
- A
- B
- Bin (Borrow In)

### Outputs
- Diff (Difference)
- Bout (Borrow Out)

### Truth Table

| A | B | Bin | Diff | Bout |
|---|---|-----|------|------|
|0|0|0|0|0|
|0|0|1|1|1|
|0|1|0|1|1|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|0|
|1|1|0|0|0|
|1|1|1|1|1|

## Files
- `subtractor.v` - Full Subtractor module
- `subtractor_tb.v` - Testbench

## Simulation
Compile: