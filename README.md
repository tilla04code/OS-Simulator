# CPU Scheduling Simulator

This project simulates the FCFS (First Come First Served) CPU scheduling algorithm in C.

## How to compile and run

1. Compile the program:
   gcc main.c -o scheduler

2. Run the program:
   ./scheduler

## Description

- The program asks the user to enter:
  - process ID
  - burst time
  - priority (stored but not used in FCFS)
- Arrival times are set automatically (0, 1, 2, 3, 4).
- The program calculates:
  - waiting time
  - turnaround time
- It also prints the average waiting time and average turnaround time.

