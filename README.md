# 🚨 Smart Gas Leakage Detection & Automatic Shut-off System

Smart Gas Leakage Detection System protects homes & industries by auto-closing main lines. Uses ESP32-C3 & sensor to detect leaks, trigger buzzers & drive solenoid valves via Omron G5Q-1 relays. Features custom LM2596/AMS1117 power circuits, USB Type-C & noise-free KiCad PCB. Under active dev 🛠️⚡

---

## 📸 Project Media & Previews

### 🔍 3D Render Views
| 3D Top-Front View | 3D Bottom/Routing View |
| :---: | :---: |
| <img src="https://drive.google.com/file/d/1CMMDwhXObLvtuzeNLT6KKFMU2CrdgBzN/view?usp=sharing" width="400"/> | <img src="https://drive.google.com/file/d/1BZcJMsVJAuz38v_FGzoavxzdfUO2AJuK/view?usp=sharing" width="400"/> |

### 🛠️ Hardware Schematics & PCB Design
| Schematic Capture (KiCad 9) | 2-Layer PCB Layout & Copper Traces |
| :---: | :---: |
| <img src="https://drive.google.com/file/d/1o2VJjTl_sBDTeEN1cD7YdBRdbGo9_HUL/view?usp=sharing" width="400"/> | <img src="https://drive.google.com/file/d/1KfplvcyfxeefTv-iGW-IMkOfqUouJPJS/view?usp=sharing" width="400"/> |

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
