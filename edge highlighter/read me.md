# Challenge 10 EdgeHighlighter

## Description
Detect rising and falling edges on an input signal and generate corresponding output pulses for each type of edge event.

## Module
| Name             | Description                                      |
|------------------|--------------------------------------------------|
| EdgeHighlighter  | Verilog module for Challenge 10 EdgeHighlighter |

## Files
| File Name            | Purpose              |
|----------------------|----------------------|
| EdgeHighlighter.v    | RTL design           |
| EdgeHighlighter_tb.v | Testbench for design |

## Testbench Guidelines
| Test Condition   | What to Check                            |
|------------------|------------------------------------------|
| Functionality     | Pulse on rising and falling transitions |
| Edge Cases        | Repeated toggles                        |
| Stability         | Reset clears both outputs               |
