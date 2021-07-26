#Security Aware Scheduling

This was done as a course project for CS3500: Operating Systems at IIT Madras

In this project we aim to detect and slow down the following 3 Microarchitectural Attacks:
    1. Rowhammer 
    2. Meltdown
    3. L1 Data cache covert channel attack

We took the kernel code v5.9.11 and made modifications in 3 files which we present in /code/

    1. ./code/core.c:   linux-5.9.11/kernel/sched/core.c
    2. ./code/fair.c:   linux-5.9.11/kernel/sched/fair.c
    3. ./code/sched.h:  linux-5.9.11/include/linux/sched.h





