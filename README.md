# Breadboard Power Supply Module ⚡🔌

A custom-designed, dual-output power supply module built specifically to fit standard MB-102 breadboards. It provides stable 5V and 3.3V power rails, making it an essential tool for prototyping embedded systems and microcontroller projects.

## 📷 Board Preview

<img width="1918" height="952" alt="Breadboard Power Supply ust" src="https://github.com/user-attachments/assets/8ec85c8a-670a-4806-90e5-9a1e0c68cc87" />
<img width="1918" height="952" alt="Breadboard Power Supply alt" src="https://github.com/user-attachments/assets/83a38cdd-ae3f-4535-ad56-22a62786c208" />


## ✨ Features
* **Dual Output Rails:** Provides both **5V** (via LM7805) and **3.3V** (via LM317) regulated outputs simultaneously.
* **Breadboard Compatible:** Pin spacing and layout are perfectly aligned for direct plug-in to standard MB-102 breadboards.
* **Power Input:** Standard barrel jack (J6) for easy connection to wall adapters, plus an onboard power switch (S1).
* **Multiple Connections:** Includes screw terminals and pin headers for versatile power distribution.
* **Visual Indicator:** Onboard LED indicates when the power is active.

## 📂 Repository Structure
* `/Gerber` - Manufacturing files (Gerbers and Drill files) ready for production.
* `breadboard_psu.pdf` - High-resolution schematic file.
* `*.kicad_pro`, `*.kicad_sch`, `*.kicad_pcb` - KiCad 8.0 project workspace files.

## 🛠️ Built With
* **[KiCad](https://www.kicad.org/)** - Open-source PCB design software.

## 🏭 Manufacturing
The fabrication files are located in the `Gerber` directory. You can directly compress this folder into a `.zip` file and upload it to your preferred PCB manufacturer (such as JLCPCB or PCBWay). 

**Board Specifications:**
* **Layers:** 2
* **Components:** Through-hole (THT) for easy hand-soldering.
* **Regulators:** LM7805 (TO-220) and LM317 (TO-220).

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
