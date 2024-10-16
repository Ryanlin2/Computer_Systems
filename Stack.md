---
tags:
  - OS_Class
---
### Description
---
- The Stack holds [[local variables]] and function call information. It grows and shrinks dynamically as functions are called and returned.
- It also keeps track of the program's execution by storing return addresses and frame pointers, ensuring the program can resume properly after functions finish executing.

### Key Features
---
- Grows downwards (toward lower memory addresses)
- Once function finishes, the stack discards local variables
- If too much memory is used in a stack. We could run into a [[Stack Overflow]]