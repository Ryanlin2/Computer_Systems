---
tags:
  - OS_Class
---
### Description
---
The process's memory is divided into different segments

### Key Features
---

- [[Code (Text)]]
- [[Data Segment]]
- [[BSS Segment]]
- [[Heap Segment]]
- [[Stack Segment]]
- [[Kernel Space]]

### Layout Summary
---
+-------------------+ 0xFFFFFFFF
|  Kernel Space     | (inaccessible to user programs)
+-------------------+ 
|  Stack            | (local variables, function call info - grows downward)
+-------------------+ 
|  Heap             | (dynamically allocated memory - grows upward)
+-------------------+ 
|  BSS              | (uninitialized global/static variables)
+-------------------+ 
|  Data             | (initialized global/static variables)
+-------------------+ 
|  Text             | (compiled program code - read-only)
+-------------------+ 0x00000000

---