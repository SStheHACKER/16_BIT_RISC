# 16-Bit RISC-Based Pipelined Processor

A 16-bit RISC processor with a custom instruction set architecture (ISA), designed and implemented using Verilog HDL. This project features a **6-stage pipeline**, **hazard mitigation**, and a functional verification suite built on **Xilinx Vivado**.

## 📅 Duration
**December 2024 – January 2025**

## 👨‍💻 Team
This was a collaborative group project. [GitHub link to contributors, if any]

---

## 🚀 Features

- **Custom 16-bit RISC Architecture**  
  Designed to execute 14 well-defined instructions including:
  - Arithmetic operations (ADD, SUB)
  - Logical operations (AND, OR, NOT, XOR)
  - Load/Store (LD, ST)
  - Control flow (BEQ, BNE, JUMP)

- **6-Stage Pipeline Architecture**  
  The processor pipeline consists of:
  1. Instruction Fetch (IF)  
  2. Instruction Decode (ID)  
  3. Register Read (RR)  
  4. Execute (EX)  
  5. Memory Access (MEM)  
  6. Write Back (WB)

- **Hazard Mitigation**
  - Implemented mechanisms to handle **data hazards** and **control hazards**.
  - Uses techniques like stalling and forwarding to ensure smooth pipeline execution.

- **Simulation & Testing**
  - Functionality verified through **testbenches**.
  - Simulated and tested using **Xilinx Vivado** to ensure performance and correctness.

---

## 🛠️ Tools & Technologies

- **Verilog HDL**
- **Xilinx Vivado 2023**
- **Git & GitHub for version control**

---
