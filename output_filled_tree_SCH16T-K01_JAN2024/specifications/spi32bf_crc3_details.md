# SPI32BF CRC specifications

**Source**: Page 33, Chunk 100  
**Category**: SPI32BF CRC specifications  
**Chunk Index**: 100

---

33 (53)
CONFIDENTIAL
6.5.2 SPI32BF CRC
SPI32BF uses 3-bit CRC (CRC3). CRC is calculated from MSB towards LSB for 29 MSB bits of the
frame, i.e., from bit 31 to 3. Generator polynomial is b1011 (POLY:4) and calculation is initialized to
b101. Final CRC is the direct value of the calculation.
Parameter Value
Name CRC-3

---

**AI Reasoning**: The content describes the CRC calculation method used in the SPI32BF, which is a technical specification detail. Placing it under 'specifications' makes it easily discoverable for those looking for technical details about the SPI32BF. The filename captures the essence of the content by highlighting the CRC aspect of SPI32BF.
