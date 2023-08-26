# MIPS_32

# Title: Verilog Implementation of a MIPS 32 Processor

## Project Summary:
The "Verilog Implementation of a MIPS 32 Processor" project aims to design and implement a simplified version of the MIPS (Microprocessor without Interlocked Pipeline Stages) 32-bit architecture using the Verilog hardware description language. The project focuses on creating a functional processor core that can execute a subset of MIPS instructions while adhering to the principles of pipelining and data path design.

## Key Objectives:

### Processor Core Design:
Develop a functional MIPS 32 processor core that consists of five pipeline stages: Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), Memory Access (MEM), and Write Back (WB).

### Instruction Set Support:
Implement a subset of MIPS instructions, covering various instruction types including R-type, I-type, and load/store instructions. Prioritize commonly used instructions to demonstrate core functionality.

### Pipelining:
Implement pipeline registers to allow multiple instructions to be processed concurrently, enhancing overall instruction throughput.

### Data Path and Control Unit:
Design and connect the data path components, including the ALU, register file, memory units, and multiplexers. Develop a control unit that generates control signals for each stage.

### Branch Handling:
Implement branch instructions and the necessary logic to handle branch predictions and target address calculations.

### Testing and Verification:
Develop a testbench to simulate the processor's functionality and validate its correctness by running a variety of test programs. Use waveform simulation to observe the flow of instructions through the pipeline and verify expected behavior.
