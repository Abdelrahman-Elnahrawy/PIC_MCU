# PIC_MCU – Disinfection Dispenser

![PIC](https://img.shields.io/badge/MCU-PIC-blue)
![XC8](https://img.shields.io/badge/Compiler-XC8-orange)
![MPLAB](https://img.shields.io/badge/IDE-MPLAB%20X-purple)
![License](https://img.shields.io/badge/License-MIT-green)
![Language](https://img.shields.io/badge/Language-C-lightgrey)

---

## 📌 Overview | نظرة عامة

**PIC_MCU** is a microcontroller-based **Automatic Disinfection Dispenser** project implemented using **Microchip PIC MCUs**.  
The system detects a user's hand using a sensor and activates a pump or valve to dispense disinfectant automatically.

مشروع **PIC_MCU** هو نظام موزع تعقيم أوتوماتيكي باستخدام متحكمات **PIC**.  
يعتمد على مستشعر لاكتشاف اليد وتشغيل مضخة أو صمام لتوزيع المطهر تلقائيًا.

---

## ⭐ Features | المميزات

- Automatic hand detection  
- Timed liquid dispensing  
- Status LED indicators  
- Simple & low-cost hardware design  
- Written in Embedded C (XC8)

- كشف تلقائي لليد  
- تحكم زمني في ضخ السائل  
- مؤشرات LED للحالة  
- تصميم اقتصادي وبسيط  
- مكتوب بلغة Embedded C

---

## 🧰 Hardware Requirements | المتطلبات الهاردوير

| Component | الوصف |
|---------|------|
| PIC MCU | PIC16 / PIC18 family |
| IR / Proximity Sensor | مستشعر كشف اليد |
| DC Pump / Solenoid | مضخة أو صمام |
| Power Supply | مصدر طاقة مناسب |
| LEDs + Resistors | لمؤشرات الحالة |

---

## 🛠 Software Requirements | المتطلبات البرمجية

- **MPLAB X IDE**
- **XC8 Compiler**
- PICkit / ICD Programmer

---

## 🚀 Getting Started | البدء

```bash
git clone https://github.com/Abdelrahman-Elnahrawy/PIC_MCU.git
Open MPLAB X

File → Open Project

Select disinfection_dispenser.X

Configure the target PIC device

Build & Program

⚙️ Build & Flashing | البرمجة ورفع الكود
Build project using XC8

Connect PICkit

Flash .hex file using MPLAB X

📁 Project Structure | هيكل المشروع
makefile
Copy code
PIC_MCU/
├── disinfection_dispenser.X
│   ├── src/        # Source files
│   ├── include/    # Header files
│   ├── Makefile
│   └── config bits
├── docs/           # Diagrams / Images (optional)
└── README.md
🧪 Usage | طريقة الاستخدام
Power on the system

Place hand near the sensor

Pump activates automatically

Disinfectant is dispensed

🔧 Possible Improvements | تطويرات مستقبلية
Adjustable delay via potentiometer

EEPROM configuration storage

Low-power sleep mode

Enclosure + PCB design

👤 Author | المؤلف
Abdelrahman Elnahrawy

📜 License
MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
