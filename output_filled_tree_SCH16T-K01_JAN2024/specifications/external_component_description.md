# Description of external components and their specifications

**Source**: Page 52, Chunk 199  
**Category**: Description of external components and their specifications  
**Chunk Index**: 199

---

52 (53)
CONFIDENTIAL
Table 80 External component description for SCH16T
Symbol Description Min Nom. Max Unit
C1 Decoupling capacitor between VREGD/VREGD2 (C1)/3p3 pin17 (C3) and 0.7 1 1.3 uF
C3 GND
(ESR <100 mOhm @ 1 MHz)
C2 Decoupling capacitor between VREGA/VREGA2 and GND 4.6 10 15 uF
(ESR <100 mOhm @ 1 MHz)
C4 Decoupling capacitor between V3p3 pin8 (C4)/VDDIO (C5) and GND 70 100 130 nF
C5 (ESR <100 mOhm @ 1 MHz)
All GND and I/O need to be connected with below exceptions.
• TA8 and TA9 shall be connected to ground, unless application needs to communicate with
multiple slaves via single Chip Select.
• If EXTRESN pin is not driven by MCU, it shall be connected to VDDIO directly or with max
20kohm PU resistor.
• N.C. pin 2 shall be left floating as indicated by schematic.

---

**AI Reasoning**: The content provides detailed specifications of external components like capacitors and their connections, which fits well under a broad 'specifications' category. This ensures easy access and findability for users looking for component details.
