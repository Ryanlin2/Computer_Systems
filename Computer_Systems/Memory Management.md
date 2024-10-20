---
tags:
  - OS_Class
---
### Description
---
Memory is divided into [[Memory Segments]]
In C we are able to manually mange memory using commands like [[Computer_Systems/malloc]] and [[free]]. 

### Code
---
maps files or anonymous memory into the process's address space
```
mmap
```

Adjusts the end of the process's heap for dynamic memory allocation
```
brk
```
### Avoid
- [[Memory Leaks]]
- [[Segment Faults]]