## PD Trigger module on Hynetek HUSB238 chip
This is a rework of [Hynetek HUSB238 evaluation board](https://www.hynetek.com/uploadfiles/site/219/files/23877051-9b40-4ae7-b10f-7e32536c2083.pdf) with minor changes. In general, i just added a fuse and reroute schematic for using available components from AliExpress.

The project is completed in Q4 2022.

## Parameters for PCB order (JLCPCB compatible)
0.8mm thickness

0.25mm min hole size

Castellated holes

## BOM list
| №  | Designator  | Qty | Description        | Manufacturer  | Name           | Package  | Link |
| -- | ----------- | --- | ------------------ | ------------- | -------------- | -------- | ---- |
| 1  | C1, C2      | 2   | 330pf MLCC         |               |                | 0402     |      |
| 2  | C3          | 1   | 1uF MLCC           |               |                | 0402     |      |
| 3  | R1          | 1   | 100kΩ smd resistor |               |                | 0402     |      |
| 4  | R2          | 1   | 10Ω smd resistor   |               |                | 0402     |      |
| 5  | R3          | 1   | 30kΩ smd resistor  |                |                | 0402     |      |
| 6  | R4, R5      | 2   | Choose a value based on the output characteristics  |    |            | 0805     |      |
| 7  | R6          | 1   | 1MΩ smd resistor   |               |                | 0402     |      |
| 8  | D1,D2,D3,D4 | 4   | TVS diod           | Littelfuse    | PGB1010603     | 0603     | [AliExpress](https://aliexpress.ru/item/32895822186.html)      |
| 9  | F1          | 1   | SMD Fuse           |               |                | 1808     | [AliExpress](https://aliexpress.ru/item/33048094198.html)      |
| 10 | J5          | 1   | USB Type-C 16pin   | GCT           | USB4505-03-0-A |          | [AliExpress](https://aliexpress.ru/item/33013020868.html)      |
| 11 | Q1          | 1   | P-MOSFET 30V       | Alpha & Omega | AON7403        | DFN3x3EP | [AliExpress](https://aliexpress.ru/item/1005003805312191.html) |
| 12 | U1          | 1   | PD controller      | Hynetek       | HUSB238        | DFN-10   | [AliExpress](https://aliexpress.ru/item/1005002906568952.html) |
