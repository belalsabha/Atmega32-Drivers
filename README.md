# Atmega32 Drivers

A collection of **drivers** for the **Atmega32** microcontroller, designed to simplify working with input/output units, serial communication, external interrupts, LCD screens, 7-segment displays, and keypads.

---

## Project Contents

### 1. Core Microcontroller Drivers
- **USART Driver:** Handles serial communication, sending and receiving data.
- **EXTI Driver (External Interrupts):** Configure and handle external interrupts.
- **IO Ports Driver:** Control digital pins and ports (Input/Output).

### 2. Main Header File
- Contains all essential definitions:
  - Memory addresses for ports and registers.
  - Digital port definitions (Port A, B, C, D).
  - Basic settings for easy microcontroller interfacing.

### 3. Display & Output Drivers
- **LCD Driver:** Control LCD screens (e.g., 16x2) for text display.
- **7-Segment Driver:** Display numbers on 7-segment displays.
- **Keypad Driver:** Read input from matrix keypads easily.
