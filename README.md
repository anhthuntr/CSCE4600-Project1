# Project 1: Process Scheduler

## Description 
For this project we'll be building a simple process scheduler that takes in a file containing example processes, and outputs a schedule based on the three different schedule types:

- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- SJF Priority
- Round-robin (RR)
- Assume that all processes are CPU bound (they do not block for I/O).

To compile:
$ go run main.go example_processes.csv

Another larger input file is provided