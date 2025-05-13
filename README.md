# CE118-Lab02: Finite State Machine (FSM) Design

## 👨‍💻 Author
- **Name**: Thach Via Sa Na  
- **Student ID**: 23520966
---

## 🧮 Arithmetic Unit (AU)

- Uses only one 16-bit full adder, with inputs selected via a 4-to-1 multiplexer.
- Efficient reuse of adder for all 4 arithmetic operations.

---

## 🔣 Logic Unit (LU)

- Uses standard bitwise gates for AND, OR, NAND, XOR.
- Output based on lower 2 bits of the opcode.

---

## 🧩 ALU Integration

- A 2-to-1 multiplexer selects between AU and LU output depending on `Opcode[2]`.
- Simulation done in **Quartus** with waveform output verification.

---

## 📹 ALU Simulation Video

[🔗 Watch on Google Drive](https://drive.google.com/file/d/101rpYPyJpe88RINGUrXbWG-XFxGfieHK/view?usp=sharing)

Test Cases:
- 7 + 6  
- 7 + 1  
- 7 - 6  
- 7 - 1  
- 111 AND 110  
- 111 OR 110  
- 111 NAND 110  
- 111 XOR 110

---

## 🧮 Additional Exercise – 4-bit Unsigned Multiplier

### 🔢 Description

- Multiplies a 4-bit input by the last digit of the student ID (6).
- Result is stored in an 8-bit output.
- Built using:
- Partial product generation
- Bit shifting
- 1-bit full adders (total: 12 used)

### 🧪 Simulation

- Verified on Quartus using waveform simulation.

---

## 🔧 Tools Used

- **Quartus Prime**
- **DE2 FPGA Kit**
- **Digital logic gates and design**
- **Multiplexers, Full Adders, Overflow Circuits**

---

## 📄 License

This project is part of coursework for CE118 at the University of Information Technology – VNU HCM. It is intended for educational purposes only.

