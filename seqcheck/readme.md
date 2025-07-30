# Challenge 08 SeqCheck

## Description
Detect three rising edges on an input signal within a 5-cycle window. If detected, assert an output flag for one clock cycle.

## Module
| Name      | Description                             |
|-----------|-----------------------------------------|
| SeqCheck  | Verilog module for Challenge 08 SeqCheck |

## Files
| File Name      | Purpose              |
|----------------|----------------------|
| SeqCheck.v     | RTL design           |
| SeqCheck_tb.v  | Testbench for design |

## Testbench Guidelines
| Test Condition   | What to Check                      |
|------------------|------------------------------------|
| Functionality     | Output high for valid 3-edge burst|
| Edge Cases        | Gaps between edges                |
| Stability         | Single pulse on match             |
