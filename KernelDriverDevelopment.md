# Bootlin's Kernel Driver Development Slides

Abreviations

ANSI C Compliler

## Linux Kernel Intro

Main roles

- Manage hardware resources
- Provide architecture and hardware independent API's
- Handle concurrent access and usage of hardware resources

System Calls

* interface betweeen kernel and user space
* System call interface is wrapped by C library (We use C library function to make system calls)

Pseudo File Systems

> Linux makes sstem and kernel information availaable in user space through psuedo file sytems
> Psuedo file systems do not occupy real storage
> 2 main types
    -  Proc = OS related info
    -  Sysfs = tree of devices connected by buses

## Linux Kernel Source Code

Programming Langauge

- Implemented in C like all UNIX systems
- No C++ used
- All code compiled with GCC
- 
