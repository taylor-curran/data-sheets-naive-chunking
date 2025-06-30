# Detailed description of pin functions and voltage levels

**Source**: Page 14, Chunk 51  
**Category**: Detailed description of pin functions and voltage levels  
**Chunk Index**: 51

---

14 (53)
Type Voltage Default
Pin # Name Description
Level state/structure
8 V3P3 External unregulated inputs for the core supply SUPPLY 3.3 V
regulators
9 GND Ground GND 0 V
10 VREGA2 Regulated core voltage for the analog circuitry. External AIN 2.5 V
capacitor connection for positive reference/supply
voltage. Connected in PCB.
11 VREGA Regulated core voltage for the analog circuitry. External AOUT 2.5 V
capacitor connection for positive reference/supply
voltage. Connected in PCB.
12 GND Ground GND 0 V
13 GND Ground GND 0 V
14 VREGD2 Regulated core voltage for the digital circuitry. External AIN 1.5 V
capacitor connection for positive reference/supply
voltage. Connected in PCB.
15 VREGD Regulated core voltage for the digital circuitry. External AOUT 1.5 V
capacitor connection for positive reference/supply
voltage. Connected in PCB.
16 GND Ground GND 0 V
17 V3P3 External unregulated inputs for the core supply SUPPLY 3.3 V
regulators
18 VDDIO Digital supply IO SUPPLY 3.3 V
19 MISO Master In Slave Out (SPI) DOUT VDDIO TRI
20 DRY_SYNC Sync input (active high) DIN/DOUT VDDIO 0/PDR
DRY (Data Ready) outputs an interrupt signal for
external MCU when the internal output registers
(gyroscope + accelerometer) have been updated.
21 SCK Serial clock (SPI) DIN VDDIO 0/PDR
22 CS Chip select (SPI) DIN VDDIO 1/PUR
23 MOSI Master Out Slave In (SPI) DIN VDDIO 0/PDR
24 HEATSINK Heatsink connection GND 0 V
1) Strong PD/PU resistance during device reset state, otherwise weak PD/PU.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content chunk provides detailed information about the pin functions, their voltage levels, and default states. This fits well under a 'pin_description' category, which is a broad and practical category for organizing such information. The filename 'pin_voltage_levels.md' captures the essence of the content, focusing on the pin descriptions and their associated voltage levels.
