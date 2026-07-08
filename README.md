# CAN Based Automotive Dashboard
AN-based automotive dashboard system for real-time vehicle data monitoring and communication using the CAN protocol.

The **CAN Based Automotive Dashboard** is an embedded systems project that monitors and displays vehicle parameters using the **Controller Area Network (CAN)** protocol. The system enables reliable, real-time communication between multiple Electronic Control Units (ECUs), allowing dashboard information to be transmitted, received, and updated efficiently.

This project demonstrates the implementation of CAN communication, Embedded C programming, and real-time automotive networking using the **PIC18F4580** microcontroller.

## Features

* Real-time CAN message transmission and reception
* Dashboard monitoring of vehicle parameters
* Reliable communication between multiple CAN nodes
* Error-resistant data transfer using the CAN protocol
* Real-time dashboard display updates
* Embedded C implementation for automotive applications

## Technologies Used

* Embedded C
* CAN Protocol
* PIC18F4580 Microcontroller
* MPLAB IDE
* XC8 Compiler
* Embedded Systems

## System Architecture

* **CAN Transmitter Node:** Sends vehicle parameter data over the CAN bus.
* **CAN Receiver Node:** Receives, validates, and processes CAN frames.
* **Dashboard Module:** Displays real-time vehicle information received from the CAN network.
* Multiple ECUs communicate using standard CAN frames for efficient and reliable data exchange.

## Project Workflow

1. Initialize CAN peripherals and communication settings.
2. Read vehicle parameters from sensors or input devices.
3. Transmit vehicle data over the CAN bus.
4. Receive and validate CAN messages.
5. Process the received data.
6. Update the dashboard display in real time.

## Compilation

Using Make:

```bash id="qjlwmn"
make
```

Or using the XC8 compiler:

```bash id="m03z3u"
xc8 *.c -o dashboard
```

## Applications

* Automotive Instrument Clusters
* Vehicle Monitoring Systems
* Automotive Diagnostics
* Industrial CAN Networks
* Real-Time Embedded Communication Systems

## Learning Outcomes

* Understanding of CAN communication protocol
* Embedded C firmware development
* Automotive networking concepts
* Real-time data transmission and reception
* CAN frame analysis and validation
* Hardware-software integration and debugging

## Future Enhancements

* Integration with additional vehicle sensors
* Support for CAN FD communication
* Data logging and diagnostics
* Graphical dashboard interface
* Wireless monitoring capabilities
