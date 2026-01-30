🖥️ Mini OS Simulator

Integrated Process Management System
This project is a modular simulation of an Operating System's core functions, designed to demonstrate process scheduling, synchronization, and resource management. It integrates CPU Scheduling, the Producer-Consumer problem, and Deadlock Prevention into a single cohesive system.

🚀 Key Features
Dynamic CPU Scheduling: Automatically switches between Priority Scheduling (non-preemptive) and Round Robin (preemptive) based on system load.

Process Synchronization: Solves the Producer-Consumer problem using Semaphores and Mutexes to manage a bounded buffer without busy waiting.

Deadlock Prevention: Implements Banker's Algorithm to ensure safe resource allocation and prevent system deadlocks.

Interactive Interface: A menu-driven command-line interface to simulate process creation, execution, and system state visualization.

🛠️ Built With
Language: C++

Concepts: Multithreading, Mutex/Semaphores, OS Algorithms

📦 How to Run
Compile the source code: g++ -o minios main.cpp process.cpp scheduler.cpp producer_consumer.cpp banker.cpp -lpthread

Run the executable: ./minios

