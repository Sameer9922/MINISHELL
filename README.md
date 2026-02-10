MINISHELL OS

A custom Unix-like command-line shell implemented in C using Linux system calls and POSIX APIs.
This project demonstrates core concepts of process management, command execution, pipes, and I/O redirection in Linux.

FEATURES

Execution of external Linux commands
Support for built-in commands (cd, pwd, exit, etc.)
Process creation using fork() and program execution using exec()
Pipes (|) for inter-process communication
Input and output redirection (<, >, >>)
Signal handling for Ctrl+C and Ctrl+Z
Environment variable handling
Robust error handling for invalid commands and system failures

TECH STACK

Language: C
Platform: Linux (Ubuntu recommended)
Concepts Used:
POSIX system calls
Process management
Inter-process communication
File descriptors & redirection
Signal handling

PROJECT STRUCTURE

minishell/
│── main.c
│── parser.c
│── execute.c
│── builtins.c
│── signal.c
│── utils.c
│── include/
│    └── minishell.h
│── Makefile
└── README.md
