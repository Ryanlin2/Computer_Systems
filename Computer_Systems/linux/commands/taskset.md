#linux_command 
This is a Linux utility used to set or retrieve the CPU affinity of a process. CPU affinity defines which CPUs (or cores) a process is allowed to run on.

Parameters
- -c 0 indicates using a cpu 0
- ./a.out is the executable
- & means do it in the background
```
taskset -c 0./a.out &
```