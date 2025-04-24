# semaphore
kernel-semaphore

# Semaphore Implementation in OS Kernel
This repository contains a C++ implementation of counting semaphores, developed as part of a custom operating system project.

# What it does
Implements functions: sem_open, sem_close, sem_wait, sem_signal, and sem_trywait
Manages thread blocking using a waiting queue
Integrated with a custom Scheduler and TCB (Thread Control Block)

# Why I’m proud of it
I learned how synchronization between threads works at a low level and how semaphores control access when multiple threads try to do the same thing. The code was written carefully to work correctly even in edge cases—like when a semaphore is closed while a thread is still waiting. Although it is not directly related to PHP, I believe it demonstrates my approach to problem-solving and a deep understanding of how systems work at their core – which helps me when working with higher-level.
