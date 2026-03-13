Project — Discrete Event Simulation (Bank Queue) 

This repository contains the code section for the first project of the Introduction to Computational Engineering course.

About the Project:

The main objective of this project is to model a real-world service system in a computer environment. By utilizing a discrete event simulation method, the project simulates a bank queue to calculate the average waiting time for customers. The modeled system consists of a single bank teller , where customers arrive at random intervals and wait in line if the teller is busy. When the teller becomes available, the next customer in the queue is served.

Model Parameters:

    Interarrival Time: Follows an exponential distribution with an average of 5 minutes.

    Service Time: Follows an exponential distribution with an average of 4 minutes.

    Simulation Length: The simulation runs for a total of 100 customers.

Features & Output Analysis:

    The simulation uses an event-based algorithm, specifically handling customer arrivals, service starts, and departures.

    The script is completely written in Python.

    To account for randomness, the simulation is executed for 10 independent runs.

    The code calculates and stores the queue length and the waiting time for each customer.

    The final output analysis includes the overall average waiting time and standard deviation.

    Wait times are visualized using a histogram or a boxplot graph.

