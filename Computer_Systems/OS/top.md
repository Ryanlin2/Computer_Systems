---
tags:
  - os_class_topic
  - OS_Class
---
### Description
---
Displays a dynamic real-time view of system processes. It shows you which processes are using the most CPU memory, and other resources.

### Key Features
---
- [[PID]]
- [[USER]]
- [[PR]]
- [[NI]]
- [[VIRT]]
- [[RES]]
- [[SHR]]
- [[S]]
- [[%CPU]]
- [[%MEM]]
- [[TIME+]]
- [[COMMAND]]
### Code
---
```
top
```

processes owned by a specific user
```
top -u <username>
```

set delay time to 5 seconds
```
top -d 5
```

##### navigating
---
quit
```
q
```

kill process
```
kill <PID>
```

change priority of process 
```
r
```



### Example Top
```
PID USER   PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND
1   root   20   0  1024  428  392 S  0.0  0.1   0:00.03 init
2   root   20   0     0    0    0 S  0.0  0.0   0:00.00 kthreadd
3   root   20   0     0    0    0 S  0.0  0.0   0:00.00 ksoftirqd/0

```
