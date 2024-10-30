---
tags:
  - os_class_topic
---
### Description
---
The act of moving a [[Process]] from one [[CPU cores|CPU core]] to another by the OS's [[Process Scheduler]]

### Key Features
---
- Load Balancing 
- Improved Resource Utilization
- Helpful when
	- [[Cache Thrashing Reduction]]
	- [[NUMA Systems]]
		- can optimize memory access patterns by moving a process closer to the memory it frequently accesses.

##### Potential Downsides
---
- [[Cache Invalidation]] may not be up to date
- [[Context-Switching]] Overhead
