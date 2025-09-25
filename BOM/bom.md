# Bill of Materials (BOM)

| Ref | Component            | Value   | Package  | Notes                         |
|-----|----------------------|---------|----------|-------------------------------|
| U1  | Voltage Regulator    | LM7805  | TO-220   | Fixed 5V regulator            |
| U2  | Voltage Regulator    | LM317   | TO-220   | Configured for 3.3V output    |
| J1  | Barrel Jack Connector| —       | DC Jack  | Power input                   |
| SW1 | Slide Switch         | —       | SPDT     | Select voltage (rail 1)       |
| SW2 | Slide Switch         | —       | SPDT     | Select voltage (rail 2)       |
| H1  | Male Header          | 2x3     | 2.54mm   | Breadboard left rail          |
| H2  | Male Header          | 2x3     | 2.54mm   | Breadboard right rail         |
| C1  | Capacitor            | 0.33µF  | Radial   | Input filter (LM7805)         |
| C2  | Capacitor            | 0.1µF   | Radial   | Output filter (LM7805)        |
| C3  | Capacitor            | 0.1µF   | Radial   | Output filter (LM317)         |
| C4  | Capacitor            | 0.33µF  | Radial   | Input filter (LM317)          |
| R1  | Resistor             | —       | Axial    | LM317 set resistor            |
| R2  | Resistor             | —       | Axial    | LM317 set resistor            |
