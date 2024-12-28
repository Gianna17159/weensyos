WeensyOS
====================

This project implements virtual memory architecture and system calls for a small operating system called WeensyOS, which supports 3MB of virtual memory and 2MB of physical memory. Kernel memory is inaccessible from user processes and processes have permission to access only its own page table. The WeensyOS version of the fork system call creates a new child process by duplicating the calling parent process. The WeensyOS version of the exit system call allows the current process to free its memory and resources and exit cleanly. The p-forkexit processes all alternate between forking new children, allocating memory, and exiting.

To run, run one of following in terminal:

make run
make run-console

To fork:

press the "f" key after running WeensyOS

To exit:

press the "e" key after running WeensyOS

