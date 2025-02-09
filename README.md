# SCR-Based Room Appliance Controller

## Project Description
This project is a **4-room appliance control system** designed using **Silicon-Controlled Rectifiers (SCRs)** in **Multisim**. The system allows regulation of **lights, fans, and a pump** in four rooms by controlling AC power through SCRs.

## Circuit Functionality
- **SCR Switching:** SCRs are used to control the AC loads by phase-angle triggering.
- **Independent Control:** Each room has separate control for its **light, fan, and pump**.
- **Voltage Regulation:** The circuit adjusts power delivery to devices using resistors, capacitors, and diodes.
- **Triggering Mechanism:** Zener diodes and resistors determine the trigger voltage to turn on the SCRs at desired angles, regulating power.

## Components Used
- **Power Source:** 220V AC, 50Hz
- **SCRs (Silicon-Controlled Rectifiers)**
- **Zener Diodes (ZN437B03, 1N5758)**
- **Resistors & Capacitors** (for timing and voltage control)
- **Potentiometers** (for user adjustments)
- **Switches & Relays** (for manual operation)
- **Oscilloscope** (for waveform analysis in simulation)

## Simulation Details
- Designed and simulated in **NI Multisim 14**.
- Uses oscilloscope to monitor output waveforms.
- Provides smooth regulation of lights, fans, and pumps in four different rooms.

## How to Use
1. **Open the project in NI Multisim 14**.
2. **Adjust potentiometers** to control the brightness of lights and speed of fans.
3. **Monitor the waveform on the oscilloscope** to observe phase-angle control.
4. **Simulate switching behavior** of pumps and lights through SCR triggering.
5. **Modify component values** to optimize performance based on requirements.

## Future Improvements
- Implement **microcontroller-based SCR triggering** for digital control.
- Add **remote or IoT-based control** for smart home integration.
- Design a **PCB layout** for real-world implementation.

---
### **Contributors**
- **Kayed Ibnet** (Roll: 2009053)
-**Abu Hanif Khan** (Roll: 2009054) 
