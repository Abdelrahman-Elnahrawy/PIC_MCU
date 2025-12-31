# PIC_MCU – Automatic Disinfection Dispenser (PIC12F675)

![MCU](https://img.shields.io/badge/MCU-PIC12F675-blue)
![Compiler](https://img.shields.io/badge/Compiler-XC8-orange)
![IDE](https://img.shields.io/badge/IDE-MPLAB%20X-purple)
![Language](https://img.shields.io/badge/Language-Embedded%20C-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview | نظرة عامة

This project implements an **Automatic Disinfection Dispenser** using the **PIC12F675** microcontroller.  
The system detects a user's hand via a sensor and activates a pump or solenoid for a fixed duration to dispense disinfectant.

مشروع **موزع تعقيم أوتوماتيكي** باستخدام المتحكم **PIC12F675**.  
يقوم النظام باكتشاف اليد عن طريق مستشعر ثم تشغيل مضخة أو صمام لفترة زمنية محددة.

---

## ⭐ Features | المميزات

- Uses **PIC12F675 (8-pin MCU)**
- Automatic hand detection
- Timed pump activation
- LED status indication
- Minimal hardware & low cost
- Written in Embedded C (XC8)

- استخدام المتحكم PIC12F675 (8 أرجل)
- كشف تلقائي لليد
- تحكم زمني في تشغيل المضخة
- مؤشرات LED للحالة
- مكونات قليلة وتكلفة منخفضة

---

## 🧠 MCU Details | مواصفات المتحكم

| Feature | Value |
|------|------|
| MCU | PIC12F675 |
| Flash | 1K words |
| RAM | 64 bytes |
| ADC | 10-bit (4 channels) |
| Oscillator | Internal 4 MHz |
| Package | 8-Pin DIP / SOIC |

---

## 🧰 Hardware Requirements | المتطلبات الهاردوير

| Component | الوصف |
|---------|------|
| PIC12F675 | المتحكم الرئيسي |
| IR / Proximity Sensor | مستشعر كشف اليد |
| DC Pump / Solenoid Valve | مضخة أو صمام |
| Transistor / Relay | دائرة تشغيل الحمل |
| LED + Resistor | مؤشر حالة |
| Power Supply | 5V أو حسب التصميم |

---

## 🛠 Software Requirements | المتطلبات البرمجية

- **MPLAB X IDE**
- **XC8 Compiler**
- PICkit 2 / PICkit 3 / PICkit 4

---

## 🚀 Getting Started | البدء

```bash
git clone https://github.com/Abdelrahman-Elnahrawy/PIC_MCU.git
Open MPLAB X

File → Open Project

Select disinfection_dispenser.X

Set device to PIC12F675

Build and program

⚙️ Build & Flashing | البرمجة ورفع الكود
Compile using XC8

Connect PICkit

Program .hex file via MPLAB X

📁 Project Structure | هيكل المشروع
PIC_MCU/
├── disinfection_dispenser.X
│   ├── src/        # Source files
│   ├── include/    # Header files
│   ├── nbproject/ # MPLAB config
│   └── Makefile
└── README.md
🧪 Usage | طريقة الاستخدام
Power on the circuit

Place hand near the sensor

Output pin goes HIGH

Pump dispenses disinfectant

🔧 Possible Improvements | تطويرات مستقبلية
Adjustable dispense time using ADC

Sleep mode for power saving

EEPROM-based configuration

PCB design and enclosure

👤 Author | المؤلف
Abdelrahman Elnahrawy
Embedded Systems Engineer

📜 License
MIT License

Copyright (c) 2025 Abdelrahman Elnahrawy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...

