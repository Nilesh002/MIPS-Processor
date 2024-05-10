# MIPS-Processor


This Verilog project simulates a simplified 5-state pipeline MIPS32 processor.

## Overview

The project consists of two Verilog modules:
- `pipe_MIPS32`: Implements the pipeline stages of the MIPS32 processor.
- `test_mips32`: Initializes and tests the `pipe_MIPS32` module.

## Modules

### `pipe_MIPS32`
- Represents the pipeline stages of a MIPS32 processor, including IF, ID, EX, MEM, and WB.
- Utilizes two-phase clocks for synchronization.
- Includes registers for PC, instruction registers, next PC, register values, memory, and control signals.

### `test_mips32`
- Initializes and tests the `pipe_MIPS32` module.
- Generates clocks, sets initial values for registers and memory, and executes a sequence of MIPS32 instructions.

## Usage

1. Clone the repository.
2. Simulate the project using a Verilog simulator.
3. Analyze simulation results to verify functionality.

## License

This project is licensed under the [MIT License](LICENSE).

