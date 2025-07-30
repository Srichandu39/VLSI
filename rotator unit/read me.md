# Challenge 09 RotatorUnit

## Description
Implement a module that rotates an 8-bit input either left or right by one position on each clock cycle based on a direction signal.

## Module
| Name         | Description                               |
|--------------|-------------------------------------------|
| RotatorUnit  | Verilog module for Challenge 09 RotatorUnit |

## Files
| File Name         | Purpose              |
|-------------------|----------------------|
| RotatorUnit.v     | RTL design           |
| RotatorUnit_tb.v  | Testbench for design |

## Testbench Guidelines
| Test Condition   | What to Check                      |
|------------------|------------------------------------|
| Functionality     | Directional bit shifting           |
| Edge Cases        | Input = 0x00 or 0xFF               |
| Stability         | Hold output with no enable         |
