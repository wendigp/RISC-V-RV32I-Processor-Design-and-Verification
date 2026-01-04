# RISC-V Processor Core (Work in Progress)

## Overview
This project focuses on the **design and verification of a RISC-V processor core**, currently under active development.  
The primary goal is to implement an **RV32I-compliant RTL design** and verify it using **SystemVerilog and UVM** in a phased manner.

This repository is being developed incrementally, following an industry-style design and verification flow.

---

## Current Status
- RTL design for basic RV32I components: **In Progress**
- Instruction decode and control logic: **In Progress**
- Verification environment: **Planned / In Progress**
- Compliance testing: **Planned**

---

## Planned Architecture
- Instruction Fetch (IF)
- Instruction Decode (ID)
- Execute (EX)
- Memory Access (MEM)
- Write Back (WB)
- Register File
- ALU
- Control Unit

---

## Planned Verification Approach
- UVM-based verification environment
- Directed and constrained-random instruction sequences
- Scoreboard-based instruction checking
- Functional coverage for RV32I instruction set

---

## Tools and Technologies (Planned)
- RTL Design: Verilog / SystemVerilog
- Verification: SystemVerilog, UVM
- Simulation: QuestaSim / Synopsys VCS

---

## Notes
This project is actively under development and will be updated as additional RTL modules and verification components are completed.
