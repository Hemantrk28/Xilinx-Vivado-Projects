# Half Adder

## Overview
A digital circuit that adds two single-bit binary numbers and produces Sum and Carry outputs.

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |

## Logic Equations
- Sum = A XOR B
- Carry = A AND B

## Simulation

![Waveform](./screenshots/hao.png)

## Design Details
- **Language:** VHDL
- **Status:** ✅ Verified

---

*Building block for full adders and multi-bit arithmetic circuits.*