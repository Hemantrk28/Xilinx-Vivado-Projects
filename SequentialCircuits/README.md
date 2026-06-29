# Sequential Circuits

## What are Sequential Circuits?

Sequential circuits are digital logic circuits where outputs depend on **current inputs AND previous states**. They have **memory** using flip-flops.

## Key Characteristics

- ✅ **Has memory** - Remember previous states
- ✅ **Clock required** - Synchronized with clock signal
- ✅ **State-dependent** - Outputs depend on past inputs
- ✅ **Feedback loops** - Current state affects next state

## Difference from Combinational Circuits

| Feature | Combinational | Sequential |
|---------|---------------|-----------|
| **Memory** | NO | YES |
| **Clock** | Not needed | Required |
| **Output depends on** | Current input only | Current input + Previous state |

## Projects Included

- Flip Flops (D, T, JK, SR)
- Shift Registers (SISO, SIPO, PISO, PIPO)
- Counters (Binary, BCD, Ring, Johnson)

## Basic Building Block: Flip Flop

A **flip-flop** stores 1 bit of information and can be in state 0 or 1.

```
Clock Signal ─┐
              ├──> Flip Flop ──> Q (Output - stores state)
Data Input ───┘
```

## Applications

✓ Counters and timers
✓ Memory elements
✓ State machines
✓ Shift registers
✓ Frequency dividers

## Design Details

- **Language:** VHDL
- **Simulator:** Vivado
- **Status:** ✅ Verified
