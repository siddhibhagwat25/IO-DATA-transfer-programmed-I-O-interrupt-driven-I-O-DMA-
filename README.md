I/O Data Transfer Simulation
📌 Project Overview

The I/O Data Transfer Simulation is an interactive web-based project developed using HTML, CSS, and JavaScript. It demonstrates three major methods of data transfer in computer organization:

Programmed I/O (Polling)
Interrupt-Driven I/O
Direct Memory Access (DMA)

The project visually explains how data moves between an I/O device, the CPU, and main memory. Users can select different transfer methods, start or pause the simulation, and observe data transfer progress, CPU activity, and execution logs.

🎯 Objectives
Understand the working principles of I/O data transfer methods.
Visualize data movement between I/O devices and main memory.
Compare CPU involvement in different transfer techniques.
Understand the role of interrupts and DMA controllers.
Provide an interactive learning tool for students studying Computer Organization and Architecture.
✨ Features
Three I/O transfer modes.
Interactive start, pause, and reset controls.
Configurable number of data blocks.
Visual representation of CPU, I/O controller, DMA controller, and main memory.
Real-time transfer progress bar.
CPU busy and available step counters.
Color-coded data block visualization.
Execution log showing transfer activities.
Comparison table for all three transfer methods.
Responsive user interface for desktop and mobile browsers.
🛠️ Technologies Used
HTML5 – Structures the web page.
CSS3 – Styles the interface and visual components.
JavaScript – Implements simulation logic and interactive controls.
⚙️ I/O Transfer Methods
1. Programmed I/O

In Programmed I/O, the CPU repeatedly checks the status of the I/O device. When the device is ready, the CPU transfers data to main memory.

Characteristics:

Continuous polling by the CPU.
High CPU involvement.
Simple implementation.
2. Interrupt-Driven I/O

In Interrupt-Driven I/O, the CPU can perform other tasks while the I/O device prepares data. When the device is ready, it sends an interrupt to notify the CPU.

Characteristics:

Reduces continuous polling.
Allows the CPU to perform other work while waiting.
Requires interrupt handling by the CPU.
3. Direct Memory Access (DMA)

DMA allows a dedicated DMA controller to transfer data
