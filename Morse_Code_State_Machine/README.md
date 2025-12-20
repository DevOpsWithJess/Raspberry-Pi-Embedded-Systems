# CS 350 Milestone Two: GPIO UART Lab

## Project Summary and Problem Being Solved
This project focused on controlling an LED on a Raspberry Pi using UART communication. The problem being solved was how to send commands from a client application to a server application that controls physical hardware. The system demonstrates how embedded devices can receive commands over a serial connection and respond reliably.

## What I Did Particularly Well
I did particularly well implementing the client–server structure and using a state machine to manage LED behavior. Separating responsibilities between the client and server helped keep the system organized, and the state machine ensured that commands such as ON, OFF, and EXIT were handled consistently.

## Where I Could Improve
One area for improvement would be expanding error handling and input validation. Adding more safeguards for unexpected input or communication issues would make the system more robust and closer to a production-ready design.

## Tools and Resources Added to My Support Network
Through this project, I added several new tools and resources to my support network, including:

- UART and serial communication documentation

- GPIO libraries for Raspberry Pi

- draw.io for creating state machine diagrams

- Python debugging and testing techniques

These resources helped reinforce core embedded systems concepts.

## Transferable Skills
This project strengthened skills that are transferable to other projects and coursework, such as:
- Client–server communication concepts

- State machine design

- Event-driven programming

- Embedded system debugging

- Interfacing software with hardware

These skills directly supported later work in the course, including the final thermostat project.

## Maintainability, Readability, and Adaptability
The project was designed with maintainability in mind by keeping the client and server code separate and clearly structured. Meaningful variable names, comments, and a documented state machine made the code easier to follow. This design allows the system to be adapted to support additional commands or hardware with minimal changes.

