# Bill of Materials (BOM)

| Ref | Component            | Value   | Package  | Notes                         |
|-----|----------------------|---------|----------|-------------------------------|
| U1  | Voltage Regulator    | LM7805  | TO-220   | Fixed 5V regulator            |
| U2  | Voltage Regulator    | LM317   | TO-220   | Configured for 3.3V output    |
| J1  | Barrel Jack Connector| —       | DC Jack  | Power input                   |
| SW1 | Slide Switch         | SW_Wuerth       | SPDT     | Select voltage (rail 1)       |
| S2, S3 | Slide Switch         | EG1218       | SPDT     | Select voltage (rail 2)       |
| J1  | Male Header          | 2x3     | 2.54mm   | Breadboard left rail          |
| J2  | Male Header          | 2x3     | 2.54mm   | Breadboard right rail         |
| C1  | Capacitor            | 10µF  | Radial   | Input filter (LM7805)         |
| C2  | Capacitor            | 0.1µF   | Radial   | Output filter (LM7805)        |
| C3  | Capacitor            | 1µF   | Radial   | Output filter (LM317)         |
| R1  | Resistor             | 330Ω       | Axial    | Current limiting for LED           |
| R2, R3  | Resistors             | 330, 560Ω       | Axial    | LM317 set resistors            |
| D1  | LED | 5.0 mm | - | Power indicator LED |

