
#LightChaser

## Description
Create a rotating LED pattern (like a running light) that moves one bit to the left every few clock cycles. Provide reset and enable inputs.

## Module
| Name         | Description                                |
|--------------|--------------------------------------------|
| LightChaser  | Verilog module for Challenge 07 LightChaser |

## Files
| File Name         | Purpose              |
|-------------------|----------------------|
| LightChaser.v     | RTL design           |
| LightChaser_tb.v  | Testbench for design |

## Testbench Guidelines
| Test Condition   | What to Check                        |
|------------------|--------------------------------------|
| Functionality     | LED rotates correctly on enable     |
| Edge Cases        | Wrap-around of pattern              |
| Stability         | Reset clears pattern                |
