## Matrix Multiplication with Multi-Processing in Python
This project demonstrates the use of Python's concurrent.futures for efficient, parallel matrix multiplication. It utilizes multi-processing to perform matrix operations across multiple CPU cores, bypassing the Global Interpreter Lock (GIL) and maximizing CPU utilization. The project measures and compares execution times across different numbers of processes and visualizes the results.

# Project Overview
This project multiplies a set of randomly generated matrices with a constant matrix using different levels of parallelism. The goal is to observe how varying the number of processes affects performance (execution time) and CPU utilization.

# Key components of the project:

Matrix Multiplication: Multiplies 500 randomly generated matrices (size 500×500) with a constant matrix of the same size.
Multi-Processing: Uses Python’s ProcessPoolExecutor to perform parallel matrix multiplication, leveraging multiple CPU cores effectively.
Execution Time Measurement: Tracks the time taken to complete the multiplication with different numbers of processes (1–8).
CPU Monitoring: Monitors and logs CPU usage at the start and end of each test to verify core utilization.
Results Visualization: Plots execution time against the number of processes to illustrate the benefits and limits of parallel processing.

# Requirements
Python 3.6+
Libraries: numpy, psutil, matplotlib
