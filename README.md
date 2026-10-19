# CAN-Based-Automotive-Dashboard

## 📌 Project Overview

The CAN-Based Automotive Dashboard is an embedded systems project developed using PIC18F4580 microcontrollers and Embedded C. It demonstrates communication between multiple Electronic Control Units (ECUs) using the Controller Area Network (CAN) protocol.

The system simulates an automotive instrument cluster by displaying real-time vehicle parameters such as speed, engine RPM, and gear position on a Character LCD (CLCD).

## 🎯 Objectives

- Understand CAN communication between multiple ECUs.
- Interface PIC18F4580 microcontrollers with vehicle parameter inputs.
- Display speed, RPM, and gear position on an LCD.
- Demonstrate distributed communication in an automotive embedded system.

## 🛠️ Technologies Used

- Microcontroller: PIC18F4580
- Programming Language: Embedded C
- Communication Protocol: CAN (Controller Area Network)
- Display: Character LCD (CLCD)
- IDE: MPLAB IDE
- Hardware: Multiple PIC microcontroller boards

## 🏗️ System Architecture

The project uses three ECUs, each with a specific responsibility.

| ECU | Responsibility |
|---|---|
| ECU 1 | Reads and transmits engine RPM data |
| ECU 2 | Reads and transmits vehicle speed data |
| ECU 3 | Receives vehicle information and displays speed, RPM, and gear position on the CLCD |

The ECUs communicate through the CAN bus, allowing vehicle parameters to be transferred between controllers.

## ⚙️ Working Principle

1. ECU 1 obtains engine RPM data and transmits it through the CAN network.
2. ECU 2 obtains vehicle speed data and transmits it through the CAN network.
3. Gear position information is processed according to the project implementation.
4. ECU 3 receives the relevant CAN messages.
5. The received vehicle parameters are displayed on the Character LCD.

## ✨ Key Features

- Multi-ECU communication using CAN.
- Real-time display of vehicle parameters.
- PIC18F4580 microcontroller interfacing.
- LCD-based dashboard simulation.
- Practical demonstration of automotive embedded systems.

## 📚 Concepts Learned

- CAN protocol and message communication.
- PIC18F4580 microcontroller programming.
- Embedded C programming.
- ADC interfacing for analog inputs, where implemented.
- Character LCD interfacing.
- Multi-controller embedded system design.

## 🚀 Applications

- Automotive instrument clusters.
- Vehicle monitoring systems.
- Distributed embedded control systems.
- Automotive communication protocol learning.

## 🔧 Tools Required

- MPLAB IDE
- PIC18F4580 development boards
- CAN communication hardware/transceivers
- Character LCD
- Suitable input circuits for speed, RPM, and gear position

## 👩‍💻 Author

**Davuluri Naga Lahari**

Electronics and Communication Engineering  
Interested in Embedded Software Development and Automotive Electronics.

## 📄 Note

This project is an educational simulation of an automotive dashboard. Actual hardware configuration, CAN message identifiers, input mechanisms, and display implementation depend on the project code and circuit design.
