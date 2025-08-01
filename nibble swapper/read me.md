
# Challenge 03 NibbleSwapper

## Description
Swap the upper 4 bits and lower 4 bits of an 8-bit input when a control signal is asserted. Maintain output stability when control is deasserted.

## Module
| Name          | Description                                 |
|---------------|---------------------------------------------|
| NibbleSwapper | Verilog module for Challenge 03 NibbleSwapper |

## Files
| File Name           | Purpose              |
|---------------------|----------------------|
| NibbleSwapper.v     | RTL design           |
| NibbleSwapper_tb.v  | Testbench for design |

## Testbench Guidelines
| Test Condition   | What to Check                   |
|------------------|---------------------------------|
| Functionality     | Swapping when control is active|
| Edge Cases        | Inputs like 0x00, 0xFF         |
| Stability         | Ensure output stays constant   |
