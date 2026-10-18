# NPPJava

NPPJava is a Java-based application that demonstrates Non-Preemptive Priority (NPP) CPU scheduling with a Gantt chart. It is designed for use with Java-compatible IDEs and requires a Java Runtime Environment (JRE) to run.

## Overview

Non-Preemptive Priority scheduling is a CPU scheduling algorithm that selects the process with the highest priority from the available processes. Once a process starts executing, it continues until completion.

NPPJava provides an educational implementation of this scheduling algorithm with a Gantt chart to visualize process execution.

## Features

- Non-Preemptive Priority CPU scheduling
- Gantt chart visualization
- Java-based implementation
- Compatible with Java development environments
- Suitable for learning operating system concepts

*Specific functionality depends on the implementation in the source code.*

## Requirements

- Latest compatible Java Runtime Environment (JRE)
- Java-compatible IDE, such as Eclipse, IntelliJ IDEA, or NetBeans
- Java Development Kit (JDK) if you need to compile the source code
- Project source files

## Installation

1. Download and install a compatible Java runtime from the official Java website: https://www.java.com/
2. Install a Java-compatible IDE if you do not already have one.
3. Download or clone this repository.
4. Open the project in your IDE.
5. Configure the Java environment if required.
6. Run the main Java class.

## Running the Project

Open the project in your Java-compatible IDE and run its main class.

If the project contains a standalone source file named `NPPJava.java`, you can compile and run it from a terminal:

```bash
javac NPPJava.java
java NPPJava
```

These commands assume that the JDK is installed and the source file contains the application's entry point. Adjust the filename or commands if your project uses a different structure.

## How It Works

Non-Preemptive Priority scheduling generally follows these steps:

1. Identify the processes ready for execution.
2. Compare their priority values.
3. Select the process with the highest priority according to the implementation's priority convention.
4. Execute the selected process until it finishes.
5. Display the execution sequence using a Gantt chart.

## Project Information

- **Project Name:** NPPJava
- **Algorithm:** Non-Preemptive Priority Scheduling
- **Language:** Java
- **Visualization:** Gantt Chart
- **Developer:** Ichiro Yamazaki
- **Build Date:** January 2024

## Disclaimer

This project is intended for educational purposes. Scheduling behavior and supported inputs depend on the actual source code.

## License

No license has been specified. All rights remain with the author unless otherwise stated.
