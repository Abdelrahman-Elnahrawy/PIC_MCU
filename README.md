# PIC_MCU — Disinfection Dispenser

A microcontroller-based automatic **Disinfection Dispenser** project built using **Microchip PIC** (MPLAB X / XC8 toolchain).  
This repository contains the PIC MCU firmware and related build files for controlling a dispenser system.

## 🧾 Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Hardware Requirements](#hardware-requirements)  
- [Software Requirements](#software-requirements)  
- [Getting Started](#getting-started)  
- [Build & Flashing](#build--flashing)  
- [Project Structure](#project-structure)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)

---

## 📌 Overview

This project implements firmware for an automatic disinfection dispenser using a **PIC microcontroller**.  
It reads sensor input (e.g., proximity or IR sensor), drives a pump or valve, and handles timing logic to dispense liquid sanitizer based on user presence.

---

## ⭐ Features

✔️ Automatic dispensing based on sensor input  
✔️ Adjustable timing between dispensations  
✔️ Status LED indicators  
✔️ Efficient code with low power usage  

*(Modify the list above according to your actual features.)*

---

## 🧰 Hardware Requirements

You will need:

| Component | Description |
|-----------|-------------|
| PIC Microcontroller | (e.g., PIC16F877A, PIC18F4550, …) |
| Proximity/IR/Ultrasonic Sensor | Detects a user’s hand |
| Pump / Solenoid Valve | Dispenses disinfectant |
| Power Supply | Suitable for PIC and motor |
| LEDs/Resistors | Status indications |
| PCB/Prototype board | For assembly |

*(Adjust based on your exact design.)*

---

## 🛠 Software Requirements

To build and flash the firmware:

- **MPLAB X IDE**
- **XC8 Compiler**
- PIC Programmer (e.g., PICkit / ICD)

---

## 🚀 Getting Started

1. Clone repository:
   ```sh
   git clone https://github.com/Abdelrahman-Elnahrawy/PIC_MCU.git
Open the project in MPLAB X:

sh
Copy code
File → Open Project → select disinfection_dispenser.X
Configure configuration bits for your PIC part.

⚙️ Build & Flashing
Build the project in MPLAB X (Run → Build Project).

Connect your PIC programmer.

Flash the generated .hex file to your microcontroller:

MPLAB X: Run → Program

📁 Project Structure
makefile
Copy code
PIC_MCU/
├── disinfection_dispenser.X   # MPLAB X project
│   ├── src/                   # C source files
│   ├── include/               # Header files
│   ├── xc*.lkr                # Linker scripts
│   └── Makefile               # Build configuration
└── README.md                  # Project overview
(Adjust according to your actual folder layout.)

📌 Usage
Once the firmware is flashed:

Power the system.

Place your hand under the dispenser.

The sensor triggers the pump/valve.

Sanitizer is dispensed automatically.

📢 Contributing
Feel free to open issues or submit pull requests to improve:

Sensor calibration

Feature enhancements

Code structure and modularity

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.



