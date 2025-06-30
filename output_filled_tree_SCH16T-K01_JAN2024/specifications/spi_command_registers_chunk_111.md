# SPI command register details

**Source**: Page 35, Chunk 111  
**Category**: SPI command register details  
**Chunk Index**: 111

---

35 (53)
CONFIDENTIAL
Command Register SPI Binary Frame SPI Hex frame
Read ACC_X2 ACC_X2 0 0 00001101 0 0 1 0000000 00000000000000000000 01110100 0x034800000074
Read ACC_Y2 ACC_Y2 0 0 00001110 0 0 1 0000000 00000000000000000000 01000010 0x038800000042
Read ACC_Z2 ACC_Z2 0 0 00001111 0 0 1 0000000 00000000000000000000 10110101 0x03C8000000B5
Read TEMP 0 0 00010000 0 0 1 0000000 00000000000000000000 10110001 0x0408000000B1
Temperature
Read STAT_SUM 0 0 00010100 0 0 1 0000000 00000000000000000000 00011100 0x05080000001C
STAT_SUM
Read STAT_SUM_S 0 0 00010101 0 0 1 0000000 00000000000000000000 11101011 0x0548000000EB
AT
Read STAT_COM 0 0 00010110 0 0 1 0000000 00000000000000000000 11011101 0x0588000000DD

---

**AI Reasoning**: The content chunk provides detailed information about SPI command registers, including binary and hex frames for reading various data points like accelerometer and temperature. This fits well under 'specifications' as it specifies how to interact with the hardware via SPI commands.
