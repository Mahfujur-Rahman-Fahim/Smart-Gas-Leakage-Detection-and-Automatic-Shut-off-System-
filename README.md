<p align="center">
  <img width="430" height="329" alt="3D Top View" src="https://github.com/user-attachments/assets/ede44cec-4ecd-4278-820d-075b558a012d" />
  <img width="412" height="331" alt="3D Bottom View" src="https://github.com/user-attachments/assets/774d96f3-55d0-47e1-a4cd-1eb8723b1754" />
</p>

# 🚨 Smart Gas Leakage Detection & Automatic Shut-off System

Smart Gas Leakage Detection System protects homes & industries by auto-closing main lines. Uses ESP32-C3 & sensor to detect leaks, trigger buzzers & drive solenoid valves via Omron G5Q-1 relays. Features custom LM2596/AMS1117 power circuits, USB Type-C & noise-free KiCad PCB. Under active dev 🛠️⚡

---

## 📸 Project Media & Previews

### 🔍 3D Render Views
| 3D Top-Front View | 3D Bottom/Routing View |
| :---: | :---: |
| <img width="430" height="329" src="https://github.com/user-attachments/assets/ede44cec-4ecd-4278-820d-075b558a012d" /> | <img width="412" height="331" src="https://github.com/user-attachments/assets/774d96f3-55d0-47e1-a4cd-1eb8723b1754" /> |

### 🛠️ Hardware Schematics & PCB Design
| Schematic Capture (KiCad 9) | 2-Layer PCB Layout & Copper Traces |
| :---: | :---: |
| <img width="530" height="371" src="https://github.com/user-attachments/assets/722d7da0-8805-4441-a925-b079ec907ff3" /> | <img width="425" height="348" src="https://github.com/user-attachments/assets/738c5e15-3711-4b65-9eaa-c6d4358c11bc" /> |

---

## ⚙️ How It Works

1. **Leak Detection:** Sensors continuously monitor gas levels. If threshold levels are breached, a signal is routed to the ESP32-C3 microcontroller.
2. **Audible & Logic Alert:** ESP32-C3 triggers the onboard high-decibel buzzer for immediate local hazard awareness.
3. **Automatic Valve Shut-off:** The Omron G5Q-1 relay actuates a Solenoid Valve to cut off the main gas line, averting fire and exposure hazards.

---

## 🚀 Key Technical Highlights

* **Integrated Microcontroller:** ESP32-C3 RISC-V Architecture for real-time sensor sampling & safety decisions.
* **Component-Level Power Architecture:** Custom onboard step-down regulation using **LM2596-ADJ** buck converter paired with **AMS1117-3.3** LDO (no pre-made modules used).
* **Modern Interface:** Type-C USB receptacle integrated for power delivery and programming.
* **Optimized Board Design:** Engineered and routed with strict noise-reduction guidelines using **KiCad 9.0**.

---

## 🛠️ Software & Tools Used

* **EDA / Hardware Design:** KiCad 9.0.7 (Schematic Capture, 3D Raytracing, PCB Layout)
* **Embedded Platform:** ESP32-C3 (C/C++ Arduino Framework / ESP-IDF)
