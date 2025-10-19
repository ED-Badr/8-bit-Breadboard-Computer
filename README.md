# 8-bit Breadboard Computer

**Status**: Active Development (Started August 2025)

Implementation of a functional 8-bit computer built from discrete logic components on breadboards. This project provides hands-on understanding of fundamental computer architecture through physical hardware construction.

## Overview

Building a complete 8-bit CPU from basic integrated circuits (ICs) to understand low-level computer organization. Each component is implemented from scratch using discrete logic gates and standard TTL chips.

### Objectives

- Implement CPU architecture using discrete components
- Design and build Arithmetic Logic Unit (ALU)
- Construct control unit with microcode
- Develop memory systems and address decoding
- Create functional instruction set architecture

## Architecture

**Specifications**
- 8-bit data bus
- 4-bit instruction set
- 16-byte RAM
- Variable clock speed (manual to ~1 MHz)

**Key Components**
- Clock module (555 timer)
- Program counter (74LS161)
- ALU (discrete logic gates)
- RAM (74LS189)
- Control unit (microcode-based)
- Register file
- Output display (7-segment)

## Implementation Status

### Completed
- [x] Component sourcing and planning
- [x] Clock module with variable frequency
- [x] Power distribution system

### In Progress
- [ ] Program counter
- [ ] Memory address register
- [ ] Bus architecture

### Planned
- [ ] ALU implementation
- [ ] Control unit and microcode
- [ ] Register file
- [ ] System integration

## Project Structure
```
├── schematics/          # Circuit diagrams
├── photos/              # Build documentation
├── docs/                # Technical documentation
├── datasheets/          # Component specifications
├── programs/            # Assembly code
└── bom.md              # Bill of Materials
```

## Technology Stack

**Components**
- 74LS series TTL logic ICs
- 555 timer circuits
- Standard passive components

**Tools**
- Breadboards and jumper wires
- Oscilloscope and logic probe
- Logisim (simulation)
- KiCad (schematics)

## Instruction Set (Planned)

- Load/Store operations
- ADD, SUB
- Jump and conditional branching
- Output operations
