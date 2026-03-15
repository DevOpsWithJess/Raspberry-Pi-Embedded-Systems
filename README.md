# Raspberry Pi Embedded Systems Projects

Author: Jessica Johnson  
Platform: Raspberry Pi  
Language: Python  

---

## Hardware Setup

![Smart Thermostat Hardware](Thermostat_Picture.png)

This project implements a smart thermostat prototype using a Raspberry Pi and external hardware components.  
The system reads temperature input and controls system behavior through a state-machine based control model.

The hardware setup includes:

• Raspberry Pi  
• LCD display for system status  
• Temperature sensor  
• Push buttons for user input  
• LEDs for system state indication  
• Breadboard and GPIO wiring

## Overview

This repository contains embedded systems projects developed using a Raspberry Pi to explore hardware–software interaction, serial communication, and state-machine based system design.

The projects demonstrate how software can directly interact with physical hardware components such as LEDs, sensors, and serial interfaces. These implementations focus on reliable device communication, structured state management, and real-time hardware control.

Core concepts explored include:

• GPIO input/output control  
• UART serial communication  
• State machine design  
• Hardware-software integration  
• Embedded systems debugging  

---

# Projects

## 1. GPIO UART State Machine

This project demonstrates how a Raspberry Pi can control physical hardware through UART serial communication using a client–server architecture.

A client application sends commands to a server running on the Raspberry Pi. The server interprets these commands and controls an LED connected to a GPIO pin using a state machine.

### Features

• UART serial communication between client and Raspberry Pi  
• Command-based control system  
• State machine for managing LED states  
• GPIO hardware control  

### Example Commands
- on
- off
-exit
- quit

These commands are received over the serial interface and interpreted by the server to control the LED output.

### Key Technologies

Python  
RPi.GPIO  
PySerial  
UART Serial Communication  

---

## 2. Smart Thermostat

This project simulates the behavior of a smart thermostat using Raspberry Pi hardware and embedded software logic.

The system monitors temperature input and transitions between system states such as heating, cooling, and idle using a structured state machine. The goal of the project is to demonstrate how embedded systems manage real-world control systems using predictable logic and hardware interfaces.

### Features

• Temperature monitoring  
• State-machine based system behavior  
• Hardware interaction through GPIO  
• Structured embedded system design  

### Example System States
- OFF
- HEAT
- COOL

The system transitions between these states depending on temperature readings and system configuration.

---

## Skills Demonstrated

Embedded Systems Development  
Raspberry Pi Hardware Integration  
Serial Communication (UART)  
GPIO Programming  
State Machine Implementation  
Hardware-Software Debugging  

---

## Repository Structure
```
Raspberry-Pi-Embedded-Systems
│
├── GPIO_UART_State_Machine
│ ├── uart_client.py
│ ├── uart_server.py
│ ├── gpio_uart_state_machine.pdf
│ └── README.md
│
├── Smart-Thermostat
│ ├── thermostat.py
│ ├── thermostat_state_machine.pdf
│ └── README.md
│
└── README.md
```

Each project folder contains its own documentation explaining implementation details and system design.

---

## What I Learned

Through these projects I gained hands-on experience with embedded systems development and how software interacts directly with hardware devices.

Key takeaways include:

• Managing hardware through GPIO interfaces  
• Implementing state machines for predictable device behavior  
• Debugging hardware communication issues  
• Structuring embedded applications for reliability  

These concepts are fundamental to IoT devices, robotics systems, and embedded control systems.

