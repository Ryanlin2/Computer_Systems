---
tags:
  - os_class_topic
---
### Description
---
Process which the OS saves the state of the currently running process and restores the state of another process so it can be executed. 

##### Types
---
- [[Voluntary Context-Switching]]
- [[Involuntary Context-Switching]]

### How it works
---
- OS saves the state (registers, program counter, etc.) of the process into its [[PCB]]
- OS loads the state of the next process to be executed into [[PCB]]
- The newly scheduled process begins or resumes its execution on the CPU.
- This switching between processes happen so quickly it looks like multiple processes are running simultaneously 

### Key Features
---
- Happens when the process [[Waiting]] or [[Process Scheduler]] decides CPU time to a different process.
- Overhead