# 4-bit-ALU in SystemVerilog

A 4-bit Arithmetic Logic Unit supporting **16 operations** with status flags  
(Zero, Positive, Negative, etc).

---

## ✅ Features

### 🔹 Supported Operations (16 total)
- ADD, SUB, INC, DEC  
- SHIFT LEFT / SHIFT RIGHT  
- ROTATE LEFT / ROTATE RIGHT  
- NOT A, NOT B  
- AND, OR, NAND, NOR, XOR, XNOR  

### 🔹 Status Flags
- Zero  
- Positive  
- Negative  
- Unsigned: GT, LT, EQ  
- Signed: GTS, LTS  

---

## 📁 Files

| File | Description |
|------|-------------|
| [`RTL_ALU.sv`](https://github.com/Rahulmahala25/4-bit-ALU/blob/main/16%20Operation%20ALU/RTL_ALU.sv)| Main ALU Design |
| [`RTL_ALU_TB.sv`](https://github.com/Rahulmahala25/4-bit-ALU/blob/main/16%20Operation%20ALU/RTL_ALU_TB.sv) | Testbench for Simulation |

---

## ▶️ Simulation

Run using any SystemVerilog simulator such as **Cadence Xcelium**:

```bash
xrun -sv RTL_ALU.sv RTL_ALU_TB.sv
