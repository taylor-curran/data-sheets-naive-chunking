# SPI transmission protocol details

**Source**: Page 29, Chunk 90  
**Category**: SPI transmission protocol details  
**Chunk Index**: 90

---

29 (53)
CONFIDENTIAL
The SPI transmission is always started with the CS falling edge and terminated with the CS rising edge.
The data is captured on the SCK's rising edge (MOSI line) and it is propagated on the SCK’s falling
edge (MISO line). This equals to SPI Mode 0 (CPOL = 0 and CPHA = 0), an example with 32-bit frame
can be seen in Figure 13 SPI frame format example (32-bit).

---

**AI Reasoning**: The content describes the SPI transmission protocol, specifically focusing on the mode and frame format. This fits well under 'specifications' as it details the operational characteristics of the SPI interface.
