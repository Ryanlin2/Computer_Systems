---
tags:
  - os_class_topic
---
 ### Description
---
The `nice` command allows you to **adjust the niceness (priority) of a process** when you start it. 

### Code
---
start a process with a specific priority 10/10 nice
```
nice -n 10 ./my_program
```

change priority
```
renice -n 5 -p <PID>
```

