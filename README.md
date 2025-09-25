# Breadboard Power Supply PCB

This project is a custom PCB that powers a breadboard with **5V** and **3.3V** rails.  
It’s designed for prototyping with microcontrollers, sensors, and other low-voltage circuits.  

The board takes input through a standard **barrel jack connector** and uses two regulators:
- **LM7805 (TO-220)** → Fixed **5V output**
- **LM317 (TO-220)** → Set up for **3.3V output**

Both voltages are available through **dual header pins**, so they can be placed directly onto both sides of a breadboard.  
Switches are added to select the active voltage for each rail.

---

## Features
-  Barrel jack input (easy power supply connection)  
-  LM7805 regulator for **5V**  
-  LM317 regulator for **3.3V**  
-  Switches to select voltage (per rail)  
-  Dual headers to power both breadboard rails  
-  Compact footprint, fits most standard breadboards  

---
## Getting Started
- Clone the repo:
    git clone https://github.com/Draycole/breadboard-power-supply-pcb.git
- Open the .pro file in KiCAD
- v9.0 and above
- Check out the schematic, board layout, or generate Gerbers for fabrication.

---
## 📊 Bill of Materials
See the [full BOM here](./BOM/bom.md).

---
## Images

<p align="center">
    <img width="1920" height="1080" alt="pcbayyeeschemaaa" src="https://github.com/user-attachments/assets/bbdf5a5e-6b38-4cc3-9a0f-8f5b976f3d49" />
    <img width="1920" height="1080" alt="pcbayylayout" src="https://github.com/user-attachments/assets/86f36572-d2e4-4393-93ef-94a87aea264c" />
    <img width="1723" height="952" alt="pcbback" src="https://github.com/user-attachments/assets/e47e99a9-918a-4bc9-b232-627f648d8fce" />
    <img width="1723" height="952" alt="pcbfront" src="https://github.com/user-attachments/assets/af2bef4b-84f4-488a-ba3e-7efcbdac8759" />
    <img width="1920" height="1080" alt="Screenshot 2025-09-24 021657" src="https://github.com/user-attachments/assets/e60f7a92-8d56-4b8b-b74d-d5d43d6369ea" />
</p>



