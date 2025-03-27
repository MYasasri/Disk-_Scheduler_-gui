The Disk Scheduler GUI is an interactive simulator that helps visualize different disk scheduling algorithms. It allows users to compare the efficiency of multiple algorithms, making it an excellent learning tool for operating system concepts. The tool implements FCFS (First-Come, First-Served), SSTF (Shortest Seek Time First), SCAN (Elevator Algorithm), and C-SCAN (Circular SCAN), providing a graphical representation of disk movement.

This project is designed to help students and professionals understand how different disk scheduling techniques perform based on seek time, request order, and system efficiency. The graphical visualization makes it easier to observe how disk scheduling algorithms handle multiple requests in real-time.

Features:
The Disk Scheduler GUI includes several key features:

Supports FCFS, SSTF, SCAN, and C-SCAN algorithms.

Provides graphical visualization for better understanding.

Allows users to compare multiple algorithms side by side.

Includes a reset option to re-run simulations easily.

Offers a user-friendly graphical interface (GUI) for interaction.


Algorithms Explained
This project implements the following four disk scheduling algorithms:

🔹 First-Come, First-Served (FCFS)
FCFS processes disk requests in the order they arrive, similar to a queue. It is easy to implement but can result in high seek times if requests are scattered across the disk.

🔹 Shortest Seek Time First (SSTF)
SSTF selects the disk request closest to the current head position, reducing overall seek time. However, it may lead to starvation, where distant requests are ignored for a long time.

🔹 SCAN (Elevator Algorithm)
SCAN moves the disk head in one direction, servicing requests as it encounters them, then reverses direction. This prevents starvation and ensures that no request is left unattended.

🔹 Circular SCAN (C-SCAN)
C-SCAN operates similarly to SCAN but only moves in one direction. Once the disk head reaches the last request, it jumps back to the beginning without servicing any requests while moving back. This provides more uniform response times compared to SCAN.

Why Use This Simulator?
The Disk Scheduler GUI is a worthwhile learning resource for students, teachers, and professionals who need to understand the intricacies of disk scheduling. By offering visualization in real-time, it bridges the gap between abstract understanding and practical implementation, simplifying it to analyze how different algorithms fare under different scenarios.
