# SPI command register details

**Source**: Page 34, Chunk 104  
**Category**: SPI command register details  
**Chunk Index**: 104

---

34 (53)
CONFIDENTIAL
Command Register SPI Binary Frame SPI Hex frame
Read STAT_RATE_Y STAT_RATE_Y 0 0 00011001 0 0 0 0000000000000000 000 0x06400000
Read STAT_RATE_Z STAT_RATE_Z 0 0 00011010 0 0 0 0000000000000000 110 0x06800006
Read STAT_ACC_X STAT_ACC_X 0 0 00011011 0 0 0 0000000000000000 100 0x06C00004
Read STAT_ACC_Y STAT_ACC_Y 0 0 00011100 0 0 0 0000000000000000 001 0x07000001
Read STAT_ACC_Z STAT_ACC_Z 0 0 00011101 0 0 0 0000000000000000 011 0x07400003
The SPI binary frame is constructed as follows:
(TA9 TA8 TA[7:0] RW 0 FrTyp AE[6:0] DATA[19:0] CRC8)

---

**AI Reasoning**: The content describes specific SPI command registers and their binary/hex frames, which are technical specifications of the hardware. Placing it under 'specifications' makes it easy to find for those looking for detailed technical information about the SPI interface.
