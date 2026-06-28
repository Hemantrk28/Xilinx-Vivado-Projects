# Half Adder

## Overview
The half adder is a digital circuit that adds two single-bit binary numbers.

## Waveform 
![Half Adder Schematic](./Screenshots/hao.png)

## Testbench code 
The waveform below shows the half adder operation through all test cases:

![Simulation Waveform](./Screenshots/hatb.png)

## Design under test code g

![Truth Table](./Screenshots/haut.png)

**Test Results:**
- Input A=0, B=0 → Sum=0, Carry=0 ✅
- Input A=0, B=1 → Sum=1, Carry=0 ✅
- Input A=1, B=0 → Sum=1, Carry=0 ✅
- Input A=1, B=1 → Sum=0, Carry=1 ✅

## Design Details
- **Language:** VHDL
- **Simulator:** Vivado
- **Status:** ✅ Complete & Verified

---

*All screenshots and design files included. Ready for FPGA implementation!*