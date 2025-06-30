# Detailed description of SCH16T pin layout and functions

**Source**: Page 13, Chunk 50  
**Category**: Detailed description of SCH16T pin layout and functions  
**Chunk Index**: 50

---

13 (53)
3.10 Pin description
Figure 1 SCH16T pin layout
Table 10 SCH16T Pin description
Type Voltage Default
Pin # Name Description
Level state/structure
1 HEATSINK Heatsink connection GND 0 V
2 Reserved Leave floating N/A
3 TA9 SPI device selection Address 1 (static). Slave DIN 0 V 0/PDR1)
addressing in SafeSPI2. Max four slaves can be
addresses by TA9:8. TA on the slave is defined by
DVIO logic level at pins TA9 and TA8.
4 TA8 SPI device selection Address 0 (static). Slave DIN 0 V 0/PDR1)
addressing in SafeSPI2. Max four slaves can be
addresses by TA9:8. TA on the slave is defined by
DVIO logic level at pins TA9 and TA8.
5 Reserved Connect to GND N/A
6 EXTRESN External reset input (low active) during normal DIN/AIN VDDIO 1/PUR1)
operation.
7 Reserved Connect to GND N/A
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides a detailed description of the pin layout and functions for the SCH16T, which fits well under the 'pin_description' category. The filename captures the essence of the content by mentioning both the pin layout and description, making it easily discoverable.
