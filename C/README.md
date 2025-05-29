
# Low Level C Projects

#### 1. **Memory Allocator (Custom malloc/free)**

* **Goal**: Understand how memory allocation works at the system level.
* **What to Build**: A custom memory manager with `my_malloc()`, `my_free()`, `my_realloc()`, and internal memory tracking.
* **Concepts to Learn**: Heap management, memory fragmentation, data alignment, `sbrk()`, system calls.
* **Stretch Goal**: Add memory leak detection and visualization for allocations.

---

#### 2. **Command Line Shell**

* **Goal**: Understand how shells like Bash work internally.
* **What to Build**: A simple shell supporting commands, piping, redirection, background jobs, and signal handling.
* **Concepts to Learn**: Process control (`fork`, `exec`, `wait`), pipes, I/O redirection, signals.
* **Stretch Goal**: Add support for scripting and command history with arrow-key navigation.

---

#### 3. **Text Editor (like nano)**

* **Goal**: Learn terminal manipulation and file I/O.
* **What to Build**: A terminal-based text editor with basic file editing and navigation.
* **Concepts to Learn**: Terminal I/O (`termios.h`), cursor manipulation, buffers, file reading/writing.
* **Stretch Goal**: Add syntax highlighting and search functionality.

---

#### 4. **Simple HTTP Server**

* **Goal**: Learn the basics of networking and HTTP protocols.
* **What to Build**: A server that serves static files over HTTP.
* **Concepts to Learn**: TCP sockets, parsing HTTP requests, handling concurrent connections using `fork` or `select`.
* **Stretch Goal**: Add rudimentary support for CGI scripts.

---

#### 5. **File System Simulation**

* **Goal**: Understand how file systems work at a low level.
* **What to Build**: A simulated file system in a single file with support for folders, files, and metadata.
* **Concepts to Learn**: File I/O, data structures (inode, FAT, etc.), block storage simulation.
* **Stretch Goal**: Implement journaling or snapshots.

---

#### 6. **Simple Database Engine**

* **Goal**: Learn storage engines and SQL query parsing.
* **What to Build**: A basic key-value or tabular data store with file-based storage and command parsing.
* **Concepts to Learn**: Data serialization, B-trees or hash indexes, parsing user input.
* **Stretch Goal**: Implement SQL-like querying and indexing.

---

#### 7. **Tiny Compiler**

* **Goal**: Learn the basics of parsing and code generation.
* **What to Build**: A compiler for a tiny custom language that outputs x86 assembly or stack-based VM code.
* **Concepts to Learn**: Lexing, parsing (recursive descent), AST, codegen.
* **Stretch Goal**: Add optimizations and error handling.

---

#### 8. **Virtual Machine**

* **Goal**: Build a low-level interpreter for a stack-based or register-based language.
* **What to Build**: A simple bytecode interpreter with support for arithmetic and control flow.
* **Concepts to Learn**: Stack/frame handling, instruction dispatch, memory management.
* **Stretch Goal**: Add support for function calls and memory allocation.

---

#### 9. **BitTorrent Client**

* **Goal**: Understand peer-to-peer protocols and network programming.
* **What to Build**: A BitTorrent downloader that supports tracker communication and basic peer interaction.
* **Concepts to Learn**: TCP/UDP, handshake protocols, hashing, file chunking.
* **Stretch Goal**: Add peer seeding and parallel downloads.

---

#### 10. **Custom Logger with Levels and Rotation**

* **Goal**: Understand file operations and logging systems.
* **What to Build**: A logger with levels (info, warning, error), timestamps, and file rotation.
* **Concepts to Learn**: File handling, timestamps, buffering, log formatting.
* **Stretch Goal**: Implement async logging with threads.

---

#### 11. **Process Scheduler Simulator**

* **Goal**: Understand how operating systems manage process scheduling.
* **What to Build**: A CLI simulator that mimics Round Robin, Priority Scheduling, SJF, and FCFS with process queue visualization.
* **Concepts to Learn**: Queues, linked lists, process states, CPU burst simulation, time slicing.
* **Stretch Goal**: Add Gantt chart visualization and I/O blocking simulation.

---

#### 12. **DNS Resolver**

* **Goal**: Learn how DNS lookup works without relying on external libraries.
* **What to Build**: A tool that performs DNS queries using UDP and parses the DNS response packets manually.
* **Concepts to Learn**: UDP sockets, DNS packet structure, byte manipulation, networking.
* **Stretch Goal**: Add caching and support for multiple record types (A, AAAA, CNAME).

---

#### 13. **Simple Linker and Loader**

* **Goal**: Understand how executable files are built and loaded.
* **What to Build**: A basic ELF (or custom) file parser that links and loads simple assembly programs.
* **Concepts to Learn**: ELF format, relocations, symbol tables, memory layout.
* **Stretch Goal**: Add support for shared libraries and dynamic loading.

---

#### 14. **Binary Diff Tool**

* **Goal**: Get comfortable with binary data and file operations.
* **What to Build**: A CLI tool to compare two binary files byte-by-byte, outputting differences.
* **Concepts to Learn**: File I/O, buffer comparison, performance tuning.
* **Stretch Goal**: Add support for patch file generation and applying patches.

---

#### 15. **Terminal Multiplexer (like tmux)**

* **Goal**: Learn terminal control, I/O multiplexing, and process management.
* **What to Build**: A tool that allows multiple terminal sessions in a single interface with keyboard shortcuts.
* **Concepts to Learn**: `select()` or `poll()`, pseudoterminals (`pty`), signal handling.
* **Stretch Goal**: Add split panes and session persistence.

---

#### 16. **Packet Sniffer**

* **Goal**: Learn about raw sockets and packet-level networking.
* **What to Build**: A tool that captures and analyzes incoming/outgoing packets.
* **Concepts to Learn**: Raw sockets, Ethernet/IP/TCP headers, byte-level parsing, `libpcap` (optional).
* **Stretch Goal**: Build a GUI with packet breakdowns and filtering options.

---

#### 17. **Regex Engine**

* **Goal**: Understand pattern matching and backtracking.
* **What to Build**: A basic regex engine that supports `.` `*` `+` `?` `[]` and grouping.
* **Concepts to Learn**: Finite automata, NFA to DFA, recursive backtracking, state machines.
* **Stretch Goal**: Add support for greedy vs non-greedy matches and POSIX syntax.

---

#### 18. **Tiny Operating System (Hobby OS)**

* **Goal**: Learn the lowest-level programming by bootstrapping an OS.
* **What to Build**: A basic kernel in C with assembly that boots, prints to screen, and handles keyboard input.
* **Concepts to Learn**: Bootloaders, interrupts, system calls, low-level hardware access.
* **Stretch Goal**: Add memory management and a simple shell.

---

#### 19. **Thread Library (User-level)**

* **Goal**: Understand how threads can be implemented in user space.
* **What to Build**: A lightweight threading library with `create`, `yield`, `join`, and `exit` functions.
* **Concepts to Learn**: Context switching, stack management, cooperative multitasking.
* **Stretch Goal**: Implement preemptive scheduling using timer signals.

---

#### 20. **Custom Tar Archiver**

* **Goal**: Learn how file archiving and formats work.
* **What to Build**: A command-line tool to create and extract `.tar` archives.
* **Concepts to Learn**: File metadata, header formatting, padding, concatenation.
* **Stretch Goal**: Add compression using zlib or custom Huffman coding.

---

#### 21. **Simple Debugger (gdb-like)**

* **Goal**: Learn how debuggers interact with running processes.
* **What to Build**: A minimal debugger that can attach to a process, set breakpoints, and inspect memory/registers.
* **Concepts to Learn**: `ptrace`, process memory, instruction stepping, register access.
* **Stretch Goal**: Add symbol resolution and a simple UI for stepping and inspecting variables.

---

#### 22. **Stack-Based Calculator**

* **Goal**: Implement an interpreter using a stack-based architecture (like Forth).
* **What to Build**: A CLI calculator that takes postfix expressions and evaluates them using a stack.
* **Concepts to Learn**: Stack implementation, expression parsing, error handling.
* **Stretch Goal**: Add custom variables, control flow, and function definitions.

---

#### 23. **Shared Memory Chat App**

* **Goal**: Understand inter-process communication using shared memory.
* **What to Build**: A chat program where multiple terminal clients can read/write to a shared memory space.
* **Concepts to Learn**: `shmget`, `shmat`, semaphores (`semop`, `semctl`), process synchronization.
* **Stretch Goal**: Add user management and persistence using mmap.

---

#### 24. **LZW Compression Tool**

* **Goal**: Dive into real-world compression algorithms.
* **What to Build**: A command-line utility to compress and decompress files using LZW.
* **Concepts to Learn**: Dictionaries, bit-level encoding, performance optimization.
* **Stretch Goal**: Add adaptive dictionary resizing and compare with gzip performance.

---

#### 25. **Assembler for a Tiny Assembly Language**

* **Goal**: Understand how assembly code is translated to machine code.
* **What to Build**: Write an assembler that converts your custom assembly syntax into binary instructions for a virtual CPU.
* **Concepts to Learn**: Parsing, opcode encoding, binary output.
* **Stretch Goal**: Add macros, labels, and symbol resolution.

---

#### 26. **C Preprocessor (Mini-CPP)**

* **Goal**: Recreate a simplified version of the C preprocessor.
* **What to Build**: A tool that supports `#define`, `#include`, and basic macro expansion.
* **Concepts to Learn**: Tokenization, file I/O, string replacement, macro handling.
* **Stretch Goal**: Handle nested includes and conditional compilation (`#ifdef`, `#ifndef`).

---

#### 27. **Filesystem Watcher**

* **Goal**: Monitor real-time changes to directories or files.
* **What to Build**: A CLI tool that watches a folder and prints changes (created, modified, deleted).
* **Concepts to Learn**: `inotify` (Linux), system events, file metadata tracking.
* **Stretch Goal**: Trigger actions on specific file changes, like re-compiling or logging.

---

#### 28. **Mini Git (Version Control)**

* **Goal**: Learn the internals of Git-style version control.
* **What to Build**: A basic VCS that tracks file changes, commits, and rollbacks.
* **Concepts to Learn**: Hashing (SHA1), diffs, file snapshots, log/history.
* **Stretch Goal**: Add branching, merging, and conflict resolution.

---

#### 29. **Dynamic Plugin System**

* **Goal**: Create a system where functions can be loaded at runtime from shared libraries.
* **What to Build**: A host program that loads `.so` files and calls exposed functions.
* **Concepts to Learn**: `dlopen`, `dlsym`, function pointers, runtime loading.
* **Stretch Goal**: Add plugin registration and discovery with metadata.

---

#### 30. **Terminal File Manager (like ranger)**

* **Goal**: Build a CLI tool for navigating the file system interactively.
* **What to Build**: A terminal-based file manager with navigation, file operations (copy, delete, move), and previews.
* **Concepts to Learn**: Terminal UI, keyboard handling, directory traversal, system calls.
* **Stretch Goal**: Add mouse support and integration with file viewers/editors.

---


#### 31. **Custom Memory Pool Allocator**

* **Goal**: Optimize allocation/deallocation using memory pools instead of system calls.
* **What to Build**: A fixed-size block allocator with custom memory chunks for fast, frequent allocations.
* **Concepts to Learn**: Pool-based allocation, memory fragmentation, free-list management.
* **Stretch Goal**: Add slab allocation or object-specific pools for types like strings, structs, etc.

---

#### 32. **In-Memory Key-Value Store (like Redis)**

* **Goal**: Build a super-fast, in-memory database.
* **What to Build**: A TCP server that accepts commands like `SET key value` and `GET key`.
* **Concepts to Learn**: Hash tables, TCP servers, string parsing, serialization.
* **Stretch Goal**: Add data persistence via AOF or snapshotting (like RDB files).

---

#### 33. **Simple ELF Parser**

* **Goal**: Understand how executable and object files are structured.
* **What to Build**: A tool that reads and displays the contents of ELF headers, sections, and symbols.
* **Concepts to Learn**: Binary file formats, file offsets, pointer arithmetic.
* **Stretch Goal**: Modify section headers or add new sections to ELF files.

---

#### 34. **Lightweight Task Scheduler**

* **Goal**: Implement cooperative multitasking with task queues and time slices.
* **What to Build**: A framework where user-defined tasks (functions) yield execution to simulate concurrency.
* **Concepts to Learn**: Context switching, state machines, cooperative multitasking.
* **Stretch Goal**: Integrate an event loop and timers for task wakeup/resume.

---

#### 35. **Unix Utility Clone (e.g., grep, wc, cat)**

* **Goal**: Rebuild core Unix tools from scratch.
* **What to Build**: Implement one or more Unix tools with all essential flags (`-i`, `-n`, etc.).
* **Concepts to Learn**: File I/O, string processing, command-line argument parsing.
* **Stretch Goal**: Create a multi-tool binary like BusyBox.

---

#### 36. **Serial Port Communication Tool**

* **Goal**: Learn to communicate with serial devices.
* **What to Build**: A program that reads from and writes to `/dev/ttyS*` or COM ports for device interaction.
* **Concepts to Learn**: Termios API, baud rates, byte-by-byte I/O.
* **Stretch Goal**: Build a serial terminal emulator with hex view and input/output logs.

---

#### 37. **Simple Terminal Emulator**

* **Goal**: Rebuild part of what terminal apps like xterm or gnome-terminal do.
* **What to Build**: A program that runs a shell and interprets basic ANSI escape codes for color and cursor.
* **Concepts to Learn**: Pseudoterminals, ANSI codes, process forking, terminal modes.
* **Stretch Goal**: Add split screens or multi-shell management.

---

#### 38. **Simple Blockchain Prototype**

* **Goal**: Learn the internals of a blockchain.
* **What to Build**: A chain of blocks, each containing data, hash of previous block, and timestamp.
* **Concepts to Learn**: Hashing (SHA256), linked structures, proof-of-work.
* **Stretch Goal**: Add a basic peer-to-peer network and consensus mechanism.

---

#### 39. **Program Dependency Analyzer**

* **Goal**: Visualize or list library and header dependencies in a C project.
* **What to Build**: A tool that recursively parses C files for `#include` and builds a dependency graph.
* **Concepts to Learn**: File parsing, tree/graph structures, recursive algorithms.
* **Stretch Goal**: Output to Graphviz `.dot` format or generate a Makefile automatically.

---

#### 40. **Low-Level Image Viewer (PPM/BMP)**

* **Goal**: Learn how raw image data is stored and rendered.
* **What to Build**: A CLI or X11-based image viewer for simple formats like PPM or BMP.
* **Concepts to Learn**: File parsing, bitmap headers, pixel rendering, basic GUI (optional).
* **Stretch Goal**: Add zooming, grayscale filtering, or format conversion.

---

#### 41. **Virtual Memory Simulator**

* **Goal**: Understand how virtual memory and paging work at a low level.
* **What to Build**: A simulation of page tables, page faults, and address translation from virtual to physical memory.
* **Concepts to Learn**: Page tables, memory mapping, TLB, segmentation vs paging.
* **Stretch Goal**: Implement LRU/clock page replacement algorithms and simulate demand paging.

---

#### 42. **Build Your Own Shell (like bash)**

* **Goal**: Learn process creation, I/O redirection, and job control.
* **What to Build**: A shell that supports commands, pipes, redirection (`>`, `<`, `|`), and basic built-ins (`cd`, `exit`).
* **Concepts to Learn**: `fork()`, `exec()`, `wait()`, signals, file descriptors.
* **Stretch Goal**: Add job control (`fg`, `bg`, `&`), tab completion, and scripting support.

---

#### 43. **VGA Graphics Library (Real Mode Simulation or Emulator)**

* **Goal**: Understand how low-level graphics rendering works with raw memory.
* **What to Build**: A simple 320x200 256-color graphics library that lets you draw pixels, lines, shapes.
* **Concepts to Learn**: Memory-mapped I/O, bit manipulation, graphics buffers.
* **Stretch Goal**: Build a full mini game or paint tool on top of your graphics library.

---

#### 44. **Hex Editor**

* **Goal**: Learn how to work with and visualize raw binary data.
* **What to Build**: A command-line tool that opens any file and displays its content in hexadecimal and ASCII.
* **Concepts to Learn**: File I/O, memory buffers, terminal formatting.
* **Stretch Goal**: Add editing, searching, highlighting, and diffing support.

---

#### 45. **PE File Parser (Windows Executables)**

* **Goal**: Understand the Windows Portable Executable (PE) format.
* **What to Build**: A tool that reads `.exe` files, dumps headers, and shows section info.
* **Concepts to Learn**: File offsets, headers, import/export tables, relocation entries.
* **Stretch Goal**: Add symbol resolution and analysis of embedded DLLs.

---

#### 46. **Real-Time Logger System**

* **Goal**: Build a high-performance logging engine for real-time systems.
* **What to Build**: A thread-safe logging system that writes to files with timestamps, log levels, and rotation.
* **Concepts to Learn**: Threads, mutexes, I/O performance, buffering, timestamps.
* **Stretch Goal**: Add log filtering, asynchronous logging, and syslog integration.

---

#### 47. **Build a Tiny Database Engine**

* **Goal**: Learn the internal mechanics of a relational database.
* **What to Build**: A key-value SQL-like database engine with a command-line REPL (`INSERT`, `SELECT`, `DELETE`).
* **Concepts to Learn**: B-Trees, paging, file storage, SQL parsing.
* **Stretch Goal**: Add indexing, transactions, and query optimization.

---

#### 48. **FAT32 Filesystem Reader**

* **Goal**: Learn how filesystem structures are laid out on disk.
* **What to Build**: A tool to read a USB drive or image file formatted with FAT32 and list files/folders.
* **Concepts to Learn**: Sector addressing, boot sectors, FAT tables, file metadata.
* **Stretch Goal**: Add write/delete file functionality and support long filenames.

---

#### 49. **Realtime Multithreaded Downloader**

* **Goal**: Master concurrent programming and I/O multiplexing.
* **What to Build**: A tool that downloads a file in parallel by dividing it into chunks using threads.
* **Concepts to Learn**: Multithreading, HTTP requests, file positioning, mutexes.
* **Stretch Goal**: Support resumable downloads and download from multiple mirrors simultaneously.

---

#### 50. **Minimal TCP/IP Stack**

* **Goal**: Learn how data is transmitted over the internet from the ground up.
* **What to Build**: A TCP/IP stack in user-space that can send/receive IP and TCP packets using raw sockets.
* **Concepts to Learn**: IP headers, TCP handshakes, checksums, retransmission, congestion control.
* **Stretch Goal**: Build a simple HTTP server on top of your custom stack.

---
