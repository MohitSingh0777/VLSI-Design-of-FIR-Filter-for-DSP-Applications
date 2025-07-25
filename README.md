# VLSI-Design-of-FIR-Filter-for-DSP-Applications
Use MATLAB to generate filter coefficients.  Implement FIR filter in Verilog.  Synthesize and simulate the design on FPGA or ASIC tools.  Compare results for area, speed, and power

## Overview
This project implements an FIR filter using Verilog. MATLAB is used to generate filter coefficients. The design is synthesized and simulated for FPGA/ASIC using Vivado and Synopsys tools.

## Features
- 8-tap FIR Filter
- MATLAB coefficient generation
- FPGA/ASIC synthesis results

## Tools Used
- MATLAB
- Verilog
- Vivado / ModelSim
- Synopsys Design Compiler

## Results
- Area: 240 LUTs (FPGA)
- Speed: 120 MHz (FPGA)
- Power: 15 mW (FPGA)

## How to Run
1. Run `fir_coeff_gen.m` in MATLAB.
2. Paste coefficients in `fir_filter.v`.
3. Simulate and synthesize in Vivado or Synopsys.
