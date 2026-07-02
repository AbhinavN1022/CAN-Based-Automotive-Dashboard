# CAN-Based-Automotive-Dashboard
AN-based automotive dashboard system for real-time vehicle data monitoring and communication using the CAN protocol.

The CAN Based Automotive Dashboard is an embedded systems project designed to monitor and display vehicle parameters through Controller Area Network (CAN) communication. The system enables reliable real-time data exchange between multiple electronic control units (ECUs), allowing dashboard information to be updated accurately and efficiently.

This project demonstrates the implementation of CAN protocol, embedded C programming, real-time communication, and automotive system design concepts.

Features
Real-time CAN message transmission and reception
Dashboard monitoring of vehicle parameters
Reliable communication between multiple CAN nodes
Error-resistant data transfer using CAN protocol
Real-time display updates
Embedded C implementation for automotive applications

Technologies Used

Embedded C
CAN Protocol
PIC18F4580 Microcontroller
MPLAB IDE
XC8 Compiler
Embedded Systems
System Architecture
CAN Transmitter Node sends vehicle parameter data.
CAN Receiver Node receives and processes CAN frames.
Dashboard displays real-time information received from the CAN network.
Multiple nodes communicate through the CAN bus using standard CAN frames.

Project Workflow

Initialize CAN peripherals and communication settings.
Transmit vehicle-related data over the CAN bus.
Receive and validate CAN messages.
Process received data.
Update dashboard display in real time.

Learning Outcomes

Understanding of CAN communication protocol
Automotive networking concepts
Embedded C firmware development
Real-time data transmission and reception
Hardware-software integration and debugging
CAN frame analysis and validation

Future Enhancements

Integration with additional vehicle sensors
Support for CAN FD communication
Data logging and diagnostics
Graphical dashboard interface
Wireless monitoring capabilities
Compilation
make
or

xc8 *.c -o dashboard

Applications

Automotive Instrument Clusters
Vehicle Monitoring Systems
Automotive Diagnostics
Industrial CAN Networks
Real-Time Embedded Communication Systems
