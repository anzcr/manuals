# MP1584EN DC-DC Buck Converter Specification Sheet

This document contains the primary technical configurations and physical dimensions for the ultra-small adjustable step-down power supply module.

---

## 📸 Product Overview
![MP1584EN Module](https://components101.com/sites/default/files/modules/Mini-MP1584-DC-DC-3A-Adjustable-Buck-Module.jpg)

---

## ⚙️ Technical Specifications

| Parameter | Specification Details |
| :--- | :--- |
| **Main Integrated Circuit** | MP1584EN (High-efficiency step-down switching regulator) |
| **Input Voltage Range** | 4.5V to 28V DC |
| **Output Voltage Range** | 0.8V to 20V DC (Adjustable via onboard potentiometer) |
| **Maximum Output Current** | 3.0A (Max peak) |
| **Continuous Output Current** | 1.5A – 2.0A (Recommended standard operating threshold without heatsink) |
| **Conversion Efficiency** | Up to 92% – 96% (Varies based on voltage differential) |
| **Switching Frequency** | ~1 MHz to 1.5 MHz |
| **Output Ripple** | < 30 mV |
| **Operating Temperature** | -45°C to +85°C |

---

## 📏 Physical Dimensions

* **Length:** 22 mm (~0.87 inches)
* **Width:** 17 mm (~0.67 inches)
* **Height:** 4 mm (~0.16 inches)
* **Form Factor:** Ultra-compact, breadboard-friendly pin arrangement

---

## 🛑 Operational Guidelines
1. **Voltage Regulation:** Turning the metal potentiometer screw counterclockwise lowers the output voltage, while clockwise increases it.
2. **Current Constraints:** If sustained usage exceeds 2.0A or the system temperature becomes noticeably hot, an external heatsink or active cooling is required.
3. **Safety Note:** This is a step-down regulator only. The input voltage must be at least 1.5V higher than your target output voltage.
