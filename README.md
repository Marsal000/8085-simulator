# 8085 Microprocessor Kit Simulator

A realistic **8085 Microprocessor Kit Simulator** built using **HTML, CSS, and JavaScript**. This project recreates the look and feel of a classic 8085 trainer kit while providing an interactive environment to write, edit, and execute 8085 machine code directly in your browser.

---

# Live Demo

###  **Try the simulator here**
**https://your-username.github.io/your-repository-name/**

> Replace `your-username` and `your-repository-name` with your GitHub details after enabling GitHub Pages.

---


# Features

- Realistic 8085 Trainer Kit interface
- Authentic Seven-Segment LED display
- Virtual hexadecimal keypad
- 64 KB memory simulation
- Memory examine and edit mode
- Register examine and edit mode
- Execute programs from any memory location
- Built-in 8085 instruction emulator
- Mobile-friendly responsive design
- Keyboard shortcuts for quick operation
- No installation required
- Runs completely inside the browser

---

# Supported Instructions

The emulator currently supports a large portion of the Intel 8085 instruction set.

## Data Transfer

- MOV
- MVI
- LXI
- LDA
- STA
- LHLD
- SHLD
- LDAX
- STAX
- XCHG

## Arithmetic

- ADD
- ADC
- SUB
- SBB
- INR
- DCR
- DAD
- DAA

## Logical

- ANA
- XRA
- ORA
- CMP
- CMA
- STC
- CMC

## Rotate

- RLC
- RRC
- RAL
- RAR

## Stack Operations

- PUSH
- POP
- XTHL
- SPHL

## Branch Instructions

- JMP
- CALL
- RET
- Conditional Jumps
- Conditional Calls
- Conditional Returns
- RST

## Machine Control

- NOP
- HLT

---

# Controls

## Command Keys

| Button | Function |
|---------|----------|
| RESET | Reset the simulator |
| EXMEM | Examine/Edit Memory |
| NEXT | Move to next memory location or register |
| PRE | Move to previous memory location |
| EXREG | Examine/Edit Registers |
| GO | Enter execution address |
| FILL | Execute program |

---

# Keyboard Shortcuts

| Key | Action |
|-----|--------|
| 0–9 | Hex input |
| A–F | Hex input |
| X or M | EXMEM |
| Enter or N | NEXT |
| P | PREVIOUS |
| R | EXREG |
| G | GO |
| Space | Execute Program |
| Esc | RESET |

---

# Getting Started

### 1. Open the simulator.

### 2. Press **EXMEM**.

### 3. Enter a 4-digit hexadecimal address.

Example:

```
2000
```

### 4. Press **NEXT**.

### 5. Enter machine code.

Example:

```
3E
```

### 6. Continue pressing **NEXT** to enter additional bytes.

### 7. Press **GO**.

### 8. Enter the starting address.

Example:

```
2000
```

### 9. Press **FILL** (or Space) to execute the program.

---

# Memory

- 64 KB Address Space
- Range: **0000H – FFFFH**
- Byte-addressable memory
- Live editing
- Sequential navigation

---

# Registers

Supported registers:

- A (Accumulator)
- B
- C
- D
- E
- H
- L

---

# CPU Components

- Program Counter (PC)
- Stack Pointer (SP)

### Flags

- Zero (Z)
- Sign (S)
- Carry (CY)
- Auxiliary Carry (AC)
- Parity (P)
