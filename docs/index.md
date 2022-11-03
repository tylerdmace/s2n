# Overview
The S2N (Soup 2 Nuts) project takes one through the process of designing and implementing an 8-bit programmable breadboard computer, the assembly language to program it, as well as a high-level language that can be compiled with the assembler as a target.

## Architecture
- 8-bit word size (data bus)
- 16-bit address size (address bus)
- No ICs (TTL components only)
- Breadboard implementation
- Assembler
- HLL and associated compiler
- Serial port for debug
- Video out

## Contents
### Clock
The clock is a TTL implementation of the 555 IC timer that is used everywhere -- we're implementing our own as our goal is to not use any ICs in our computer.
#### Parts
- 1x powered breadboard
- 2x 1K ohm resisters
- 2x 10K ohm resisters
- 11x 4.7k ohm resisters
- 11x 2n3904 NPN transistors
- 9x 2n3906 PNP transistors

### Bus
### Registers
### Program Counter
### MIR
### Memory
### Control Unit
### ALU
### Output

## Tools
### Software
- Logisim
- TinkerCAD (Autodesk)
- Verilog 2005 / SystemVerilog

### Hardware
- 1x 60W pencil solder iron
- 1x vice
- 1x third hand
- 1x magnifying glass
- 1x needle nose pliers
- 1x wirecutters
- 50x powered breadboards
- 1x 3.3v / 5v breadboard power supply
- 250x 1Kohm resisters
- 50x 100ohm resisters

## References
- The CARDIAC computer
- The LMC computer
- The LC3 and LC3b computers
- The Hack computer (The Elements of Computing Systems)
- The SP1, SP2, and SP3 computers (Digital Computer Electronics)
- The 8008, 8080, and 8085 microprocessors from Intel
- The 6502 microprocessor from MOS Technology
- The Z80 microprocessor from Zilog