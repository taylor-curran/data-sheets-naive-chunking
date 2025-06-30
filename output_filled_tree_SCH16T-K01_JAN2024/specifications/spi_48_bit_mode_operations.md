# SPI 48-bit mode operations and frame structure

**Source**: Page 34, Chunk 105  
**Category**: SPI 48-bit mode operations and frame structure  
**Chunk Index**: 105

---

6.6.2 48-bit mode operations
The SPI binary frame is constructed as follows:
(TA9 TA8 TA[7:0] RW 0 FrTyp AE[6:0] DATA[19:0] CRC8)
Command Register SPI Binary Frame SPI Hex frame
EOI CTRL_MODE 0 0 00110101 1 0 1 0000000 00000000000000000011 10001101 0x0D680000038D

---

**AI Reasoning**: The content describes the structure and operation of a 48-bit SPI mode, which is a technical specification of how the device communicates using SPI. This fits well under 'specifications' as it details a specific operational mode and its binary frame construction.
