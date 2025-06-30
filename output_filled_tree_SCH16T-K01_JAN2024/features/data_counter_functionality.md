# Description of the data counter feature and its usage in SPI protocol

**Source**: Page 27, Chunk 83  
**Category**: Description of the data counter feature and its usage in SPI protocol  
**Chunk Index**: 83

---

5.4.5 Data counter
Data counter is supported for decimated outputs RATE_XYZ2 and ACC_XYZ2. Value of data counter is
increased by one when a new sample is available from corresponding RATE/ACC channel. It can be
understood as an index for the data output values. Using the data counter, the user can monitor that
every wanted sample has been acquired and that the same sample has not been read twice.
When using 48-bit SPI protocol, 4-bit data counter value is included in MISO response frame. Data
counter can be also used in 32-bit mode by reading DCNT_RATE and DCNT_ACC register values via
SPI command. Register locations are described in chapter 7.3.
Using frequency counter, user can acquire accurate clock information from component internal MCLK
via SPI. The value of frequency counter register is increased by one with every 16th rising edge of

---

**AI Reasoning**: The content describes a specific feature of the hardware related to data counting and its implementation in SPI protocol. It fits well under 'features' as it details a functional aspect of the device. The filename captures the essence of the content, focusing on the data counter functionality.
