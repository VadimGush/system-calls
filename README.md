# system-calls

Just a list of system calls that I often use. With the header file from a specification and a link to documentation.

| Specification | Header | System call | Description | Link |
|---|---|---|---|---|
| POSIX | `fcntl.h` | `open()` | Open a file, create a file |
| POSIX | `unistd.h` | `read()` | Read from a file descriptor |
| POSIX | `unistd.h` | `write()` | Write to a file descriptor |
| POSIX | `unistd.h` | `close()` | Close a file descriptor |
| POSIX | `sys/stat.h` | `stat()/fstat()` | Get file information (size, time, i-node...) |
| |
| POSIX | `dlfcn.h` | `dlopen()` | Open shared object | [man7](https://man7.org/linux/man-pages/man3/dlopen.3.html) |
| |
| POSIX | `sys/socket.h` | `socket()` | Create a socket | [man7](https://man7.org/linux/man-pages/man2/socket.2.html) |
| POSIX | `sys/socket.h` | `connect()` | Connect through a socket | [man7](https://man7.org/linux/man-pages/man2/connect.2.html) |
| POSIX | `netdb.h` | `getaddrinfo()` | Resolve an address | [man7](https://man7.org/linux/man-pages/man3/getaddrinfo.3.html) |
