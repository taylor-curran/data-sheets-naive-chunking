# Description of SPI CRC and sensor data counter

**Source**: Page 30, Chunk 93  
**Category**: Description of SPI CRC and sensor data counter  
**Chunk Index**: 93

---

30 (53)
CONFIDENTIAL
SYMBOL DESCRIPTION
accurate info is seen from sensor status (S1:S0).
DCNT A wrapping 4-bit sensor data counter.
CRC8 8-bit CRC reference for SPI48BF. Calculated over bits 47 to 8.
(C7:0)
CRC3 3-bit CRC reference for SPI32BF. Calculated over bits 31 to 3.
(C2:0)
SCH16T SPI supports several slave devices on single bus by using either multiple chip select lines, one
for each slave, or with one common chip select (CS) and using TA9 and TA8 pins to enable logical

---

**AI Reasoning**: The content primarily describes the CRC references and sensor data counter related to the SPI interface, which fits well under specifications as it details specific functionalities and features of the hardware.
