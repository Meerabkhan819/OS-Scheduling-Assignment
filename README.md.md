# OS Assignment 1: CPU Scheduling Algorithms

 Student Details:
Name: Mehrab Un Nisa Malik
Registration Number: 8656
University:Abasyn University, Islamabad Campus
Semester: 6th
Course: Operating Systems (OS)
Submitted To:DR Sadaf Tanveer

## Project Overview
This repository contains C++ implementations of the following CPU Scheduling Algorithms as per Assignment 1 guidelines:
1. Q1: First Come First Serve (FCFS) Scheduling
2. Q2:Non-Preemptive Shortest Job First (SJF) Scheduling
3. Q3: Non-Preemptive Priority Scheduling
4. Q4:Round Robin (RR) Scheduling
5.Q5: Comparison of Scheduling Algorithms

---

## Q5: Comparison & Analysis
When running the same set of processes across FCFS, SJF, and Priority Scheduling:
SJF (Shortest Job First) consistently gives the **lowest Average Waiting Time (AWT) because it minimizes the waiting time of shorter processes (prevents Convoy Effect).
FCFS is simple but can result in high waiting time if a long process arrives first.
Priority Scheduling serves processes based on importance rather than length or time of arrival.

Conclusion:SJF is the best-performing algorithm in terms of minimizing average waiting time.