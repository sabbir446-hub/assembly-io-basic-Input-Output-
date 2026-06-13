# assembly-io-basic-Input-Output-
# 8086 Assembly Character Echo

A simple 8086 Assembly Language program written in MASM/TASM syntax that demonstrates basic Input/Output (I/O) operations using DOS interrupts (`INT 21H`).

### How It Works:
1. **Input:** Takes a single character input from the user via keyboard (`AH = 1`).
2. **Newline:** Automatically prints a Carriage Return (`0DH`) and Line Feed (`0AH`) to move the cursor to the next line.
3. **Output:** Echoes (prints) the exact same input character back onto the screen (`AH = 2`).
4. **Exit:** Safely terminates the program and returns control to the operating system (`AH = 4CH`).

This code serves as a foundational template for understanding register management and basic hardware interaction in low-level programming.
