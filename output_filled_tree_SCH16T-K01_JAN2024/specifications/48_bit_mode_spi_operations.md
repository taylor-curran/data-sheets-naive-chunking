# Details of 48-bit mode operations and their SPI frames

**Source**: Page 34, Chunk 106  
**Category**: Details of 48-bit mode operations and their SPI frames  
**Chunk Index**: 106

---

Table 23 48-bit mode operations and their equivalent SPI frames
Command Register SPI Binary Frame SPI Hex frame
EOI CTRL_MODE 0 0 00110101 1 0 1 0000000 00000000000000000011 10001101 0x0D680000038D
EN_SENSOR CTRL_MODE 0 0 00110101 1 0 1 0000000 00000000000000000001 11010011 0x0D68000001D3
Set LPF0 to CTRL_FILT_R 0 0 00100101 1 0 1 0000000 00000000000000000000 00010110 0x096800000016
Set LPF0 to CTRL_FILT_A 0 0 00100110 1 0 1 0000000 00000000000000000000 00100000 0x09A800000020

---

**AI Reasoning**: The content provides specific details about the 48-bit mode operations and their corresponding SPI frames, which are technical specifications of the hardware. Grouping this under 'specifications' makes it easily accessible for users looking for detailed operational data. The filename captures the essence of the content, focusing on the 48-bit mode and SPI operations.
