
# Operating System Simulator

An educational Operating System Simulator developed in Java to demonstrate fundamental operating system concepts through algorithm-based simulations.

## Project Overview

The project aims to simulate essential operating system components, including process management, CPU scheduling, memory allocation, disk scheduling, and deadlock detection.

The main goal is to connect theoretical operating system concepts with practical programming, data structures, and algorithms.

## Planned Features

### Process Management
- Process creation and termination.
- Process identification (PID).
- Process state management.
- Process priority assignment.
- Ready and waiting queues.

### CPU Scheduling
- First Come First Served (FCFS).
- Shortest Job First (SJF).
- Shortest Remaining Time First (SRTF).
- Round Robin (RR).
- Priority Scheduling.

### Memory Management
- Memory allocation and deallocation.
- First Fit.
- Best Fit.
- Worst Fit.
- Memory fragmentation analysis.

### Disk Scheduling
- FCFS.
- SSTF.
- SCAN.
- C-SCAN.

### Deadlock Management
- Resource allocation.
- Deadlock detection.
- Resource Allocation Graph.
- Banker's Algorithm.

### Visualization
- Process monitoring.
- CPU scheduling visualization.
- Memory allocation visualization.
- Gantt charts.
- Simulation statistics.

## Technologies

- Java 21+
- Maven
- JavaFX
- JUnit 5
- Java Collections Framework
- Java Concurrency API

## Project Structure

    Operating-System-Simulator/
    ├── src/
    │   ├── main/
    │   │   ├── java/
    │   │   │   └── com/oss/
    │   │   │       ├── Main.java
    │   │   │       ├── core/
    │   │   │       ├── process/
    │   │   │       ├── cpu/
    │   │   │       ├── memory/
    │   │   │       ├── disk/
    │   │   │       ├── deadlock/
    │   │   │       └── simulation/
    │   │   └── resources/
    │   └── test/
    │       └── java/
    ├── docs/
    ├── pom.xml
    ├── LICENSE
    └── README.md

## Build and Execution

Compile:

    mvn clean compile

Run tests:

    mvn test

Package:

    mvn package

## Development Roadmap

- [ ] Core application.
- [ ] Process Management.
- [ ] CPU Scheduling.
- [ ] Memory Management.
- [ ] Disk Scheduling.
- [ ] Deadlock Management.
- [ ] JavaFX Dashboard.
- [ ] Automated Testing.
- [ ] Documentation.

## Learning Objectives

- Object-Oriented Programming.
- Data Structures and Algorithms.
- Operating System Fundamentals.
- Process Scheduling.
- Memory Management.
- Concurrency.
- Software Engineering.

## Limitations

This project is an educational simulator. It does not manage actual host operating system processes, physical memory, or disk devices.

Features are planned and will be implemented incrementally.

## License

This project is licensed under the MIT License.
