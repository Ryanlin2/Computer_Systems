---
tags:
  - os_class_topic
---
### Description
---
A diagnostic tool used in Linux to trace system calls made by a program. 

### Key Features
---
- Allows you to see how program interacts with OS such as 
	- file access
	- memory allocation
	- process creation 
	- network creation

### Example Output
---
```
strace ls 
```

```
execve("/bin/ls", ["ls"], 0x7ffec5f65a10 /* 55 vars */) = 0
brk(NULL)                               = 0x55a6b19a5000
access("/etc/ld.so.preload", R_OK)      = -1 ENOENT (No such file or directory)
openat(AT_FDCWD, "/etc/ld.so.cache", O_RDONLY|O_CLOEXEC) = 3
fstat(3, {st_mode=S_IFREG|0644, st_size=12345, ...}) = 0
mmap(NULL, 12345, PROT_READ, MAP_PRIVATE, 3, 0) = 0x7f8b64852000
close(3)                                = 0
openat(AT_FDCWD, "/usr/lib/x86_64-linux-gnu/libc.so.6", O_RDONLY|O_CLOEXEC) = 3
...
write(1, "file1  file2  file3\n", 20)   = 20
close(3)                                = 0
exit_group(0)                           = 0

```
