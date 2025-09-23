# Breadboard Power Supply PCB

This project is a custom PCB that powers a breadboard with **5V** and **3.3V** rails.  
It’s designed for prototyping with microcontrollers, sensors, and other low-voltage circuits.  

The board takes input through a standard **barrel jack connector** and uses two regulators:
- **LM7805 (TO-220)** → Fixed **5V output**
- **LM317 (TO-220)** → Configured for **3.3V output**

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
