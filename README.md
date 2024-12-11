# Uncommon Assembly Code Errors

This repository demonstrates some uncommon and subtle errors that can occur in assembly language programming. These errors are often difficult to debug because they may not always lead to immediate crashes but can cause unpredictable behavior.

The examples highlight issues such as:

* **Memory Access Violations:** Accessing memory outside the allocated bounds of an array.
* **Register Misuse:** Incorrect use of registers leading to unexpected values or overwritten critical data.
* **Stack Imbalance:** Errors in push and pop operations resulting in a corrupted stack.
* **Integer Overflow:** Potential integer overflow if calculations exceed the maximum value a register can hold.

The `bug.asm` file contains the erroneous code, while `bugSolution.asm` provides the corrected version with explanations.