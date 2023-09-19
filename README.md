# system-calls

| Specification | Header | System call | Description |
|---|---|---|---|
| POSIX | `fcntl.h` | `open()` | Open a file, create a file |
| POSIX | `unistd.h` | `read()` | Read from a file descriptor |
| POSIX | `unistd.h` | `write()` | Write to a file descriptor |
| POSIX | `unistd.h` | `close()` | Close a file descriptor |
| POSIX | `sys/stat.h` | `stat()/fstat()` | Get file information (size, timestamp, i-node, etc.) |
