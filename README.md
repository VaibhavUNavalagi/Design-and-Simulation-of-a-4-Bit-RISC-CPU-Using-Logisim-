# 🚀 Design and Simulation of a 4-Bit RISC CPU Using Logisim  

![Static Badge](https://img.shields.io/badge/Project-CPU%20Design-blue)  
![Static Badge](https://img.shields.io/badge/Tool-Logisim-green)  
![Static Badge](https://img.shields.io/badge/Architecture-Harvard-orange)  

---

## 📌 Introduction  
This project demonstrates the design and simulation of a **4-Bit RISC CPU** using **Logisim**, a popular educational tool for digital circuit design.  
The CPU follows the **Harvard Architecture**, separating program and data memory for simplicity and clarity.  

It consists of essential components such as:  
- **Program Counter (PC)**  
- **Instruction Register (IR)**  
- **Arithmetic Logic Unit (ALU)**  
- **General Purpose Registers (R0–R3)**  
- **Control Unit**  
- **7-Segment Display for testing**  

The aim is to **bridge the gap between theoretical computer architecture and practical digital design** through a minimal yet functional CPU.  

---

## ✨ Features  
✔️ Harvard Architecture with separate code & data memory  
✔️ Basic RISC-style instruction set  
✔️ Supports ALU operations (`ADD`, `AND`, `OR`, `XOR`)  
✔️ General-purpose register file (R0–R3)  
✔️ Modular ALU design for easy extension  
✔️ Interactive testing via **7-Segment Display**  
✔️ Fully simulated in **Logisim** (no extra tools required)  

---

## 🔹 Why Logisim?  
- 🖥️ **Visual Understanding** → Drag-and-drop interface for quick circuit prototyping  
- 📘 **Educational Value** → Great for learning computer architecture fundamentals  
- ⚡ **Lightweight & Portable** → Runs on any system without heavy setup  
- 🧩 **Customizability** → Easy to extend with new instructions, registers, or memory units  
- 🔍 **Debugging Made Simple** → In-built clocks, probes, and testing devices  

---

## ⚙️ ALU Design  
The **Arithmetic Logic Unit (ALU)** is the computational heart of the CPU.  

**Key Features:**  
- 4-bit inputs from register file  
- Supports **RISC instructions**: `ADD`, `AND`, `OR`, `XOR`  
- Flags: **Zero** & **Carry** (future use: conditional branching)  
- Modular structure → easy extension for `SUB`, `NOT`, `SHIFT`  

<img width="1919" height="1017" alt="Image" src="https://github.com/user-attachments/assets/dd3e20bc-d369-4067-9aa5-ad9702816fc2" />

---

## 🖥️ Final CPU Design  
The complete **4-Bit RISC CPU** integrates all building blocks:  

- **Program Counter (PC)** → Keeps track of the next instruction  
- **Instruction Register (IR)** → Holds and decodes the instruction  
- **Control Unit** → Generates control signals for execution  
- **ALU** → Performs arithmetic & logic operations  
- **Register File (R0–R3)** → Temporary storage for operands/results  
- **Memory Unit** → Program & data separation  
- **7-Segment Display** → For debugging & output visualization  

<img width="1919" height="1017" alt="Image" src="https://github.com/user-attachments/assets/ab546f7c-aa53-465f-92c2-e367ccbe4438" />

---

## 🧾 Instruction Set  
| Opcode | Mnemonic | Operation | Example |
|--------|----------|-----------|---------|
| 0001   | ADD      | R[d] ← R[s1] + R[s2] | ADD R1, R2 → R1 = R1 + R2 |
| 0010   | AND      | R[d] ← R[s1] AND R[s2] | AND R1, R2 |
| 0011   | OR       | R[d] ← R[s1] OR R[s2] | OR R1, R3 |
| 0100   | XOR      | R[d] ← R[s1] XOR R[s2] | XOR R2, R3 |  

---

## 🔮 Future Improvements  
- Add more instructions (`SUB`, `LOAD`, `STORE`, `JUMP`)  
- Implement branching & conditional execution  
- Add stack pointer & subroutine support  
- Extend design to 8-bit / 16-bit CPU  
- Integrate assembler for easier programming  

---

## 🏁 Conclusion & Future Work  
This project successfully demonstrates the **fundamentals of CPU design** in a clear and modular way. By simulating a 4-bit RISC processor, it lays the foundation for exploring **how real-world processors are built and optimized**.  

In terms of **real-world relevance**:  
- Similar concepts are used in **microcontrollers** (Arduino, PIC, ARM Cortex-M) that power IoT devices.  
- The Harvard Architecture is applied in **DSP processors** for efficient handling of multimedia data.  
- The RISC philosophy influences modern CPUs like **ARM processors** found in smartphones and embedded systems.  

