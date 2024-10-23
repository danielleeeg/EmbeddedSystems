# EmbeddedSystems
## Summary
This project involves developing and embedded system application for a Texas Instruments board, CC3220S. This board reads temperature data from I2C sensors and controls an LED in a way that conveys the current temperature in relation to a setpoint. It also sends real-time updates using an UART peripheral. Two buttons are used to adjust the setpoint and a task scheduler is used for timer-based operations. 
The main problem that this program addressed was creating a responsive system to monitor and regulate temperature while communicating status updates over UART. The code handles real-time interrupts and integrates sensor reading, task scheduling, and UART communication for a streamlined user experience. 

## Strengths
One area done particularly well in this project was the structuring of the code to handle multiple peripherals and functions effectively, such as the integration of GPIO, UART, I2C, and Timer. Additionally, setting up a task scheduler improved code modularity and ensured tasks ran at precise intervals. This is critical for real-time applications. 

## Areas of Improvement
One potential area of improvement is the optimization of memory usage and readability. Although the code is functional, adding more modularity by breaking down functions into even smaller pieces, and better organizing global variables could help with scalability. More comprehensive error handlining for UART and I2C failures could also improve the system’s reliability. 

## Tools and Resources for Support
For future projects, adding resources such as embedded system development tools and learning platforms like TI forums or Stack Overflow for troubleshooting could be beneficial. Engaging with more literatures on task scheduling and interrupt handling in real-time systems could also enhance depth of understanding. 

## Transferrable Skills
The task scheduler design, interrupt-driven programming, and integration of multiple drivers all skills that can be transferred to other systems and projects. Their interactions with real-time data are not unique in the field of embedded system development in particular. 

## Maintainability, Readability, and Adaptability
There were several measures taken to ensure the program would be easily maintained, read, and adapted. First, comments were liberally used throughout the program to describe key functions and logic. This will make it much easier for future contributors to understand the code itself, as well as the intentions of the original programmer. Use of modular, descriptively-named functions allows for faster understanding and debugging of code. Next, the task scheduler adds adaptability code because additional tasks can be easily added to the existing program with minimal restructuring. Finally, the code uses a consistent and clear naming convention that leaves little ambiguity in variable and functions purposes. This compliments the comments throughout the code by adding additional context to key elements of the code. 
