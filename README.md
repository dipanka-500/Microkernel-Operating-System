# Microkernel-Operating-System



Overview
This project is a microkernel-based operating system developed from scratch using C, C++, and x86 Assembly. It features a minimalistic kernel design, enabling efficient CPU scheduling, process synchronization, and memory management tailored for resource-constrained embedded platforms.

Features
Microkernel Design:

Modular architecture for ease of extension and debugging.
Supports inter-process communication (IPC) for user and system processes.
Round-Robin CPU Scheduling:

Implements time-slice-based scheduling to ensure fair process execution.
Semaphore-Driven Synchronization:

Provides robust synchronization for critical sections, avoiding race conditions and deadlocks.
Paging-Based File System:

Efficient memory allocation using paging for file system operations.
Integrates Direct Memory Access (DMA) for faster data handling.
Custom Bootloader:

Written in x86 Assembly.
Handles initialization and loads the OS seamlessly onto the target hardware.
