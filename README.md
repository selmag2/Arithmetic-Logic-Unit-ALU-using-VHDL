# 🧮 VHDL Arithmetic Logic Unit (ALU)

## 📖 Description
The **Arithmetic Logic Unit (ALU)** is a fundamental building block of modern **Central Processing Units (CPUs)**. It performs arithmetic, logical, shift, rotate, and comparison operations required for instruction execution.

This project presents the **design and implementation of a fully functional ALU using VHDL**. The ALU is described using synthesizable VHDL code and supports a wide range of operations commonly found in processor architectures.

---

## 🎯 Project Goals
- Design a complete ALU using **VHDL**
- Implement arithmetic, logic, shift, rotate, and comparison operations
- Demonstrate correct ALU behavior through simulation
- Provide clean, modular, and reusable HDL code

---

## ⚙️ ALU Features
- Combinational ALU design  
- 16 supported operations  
- Opcode-based operation selection  
- Synthesizable VHDL implementation  

---

## 🔢 Supported Operations

### Arithmetic
- Addition  
- Subtraction  
- Multiplication  
- Division  

### Shift & Rotate
- Logical Shift Left  
- Logical Shift Right  
- Rotate Left  
- Rotate Right  

### Logical
- AND  
- OR  
- XOR  
- NOR  
- NAND  
- XNOR  

### Comparison
- Greater Than (`A > B`)  
- Equality (`A = B`)  

---

## 🔢 Opcode Mapping

| Opcode | Operation |
|-------|----------|
| 0000 | Addition |
| 0001 | Subtraction |
| 0010 | Multiplication |
| 0011 | Division |
| 0100 | Logical Shift Left |
| 0101 | Logical Shift Right |
| 0110 | Rotate Left |
| 0111 | Rotate Right |
| 1000 | AND |
| 1001 | OR |
| 1010 | XOR |
| 1011 | NOR |
| 1100 | NAND |
| 1101 | XNOR |
| 1110 | Greater Than |
| 1111 | Equal |

---

## 🧠 ALU Architecture
- **Inputs:** Operand A, Operand B, Opcode  
- **Output:** `ALU_Out`  
- 4-bit opcode used for operation selection
- Comparison operations return `1` or `0`

---

## 🛠️ Technologies
- **Language:** VHDL  
- **Design:** Combinational Logic  
- **Tools:** ModelSim / Vivado / GHDL  

---

## 📁 Project Structure
```text
├── alu.vhd
├── testbench.vhd
└── README.md
