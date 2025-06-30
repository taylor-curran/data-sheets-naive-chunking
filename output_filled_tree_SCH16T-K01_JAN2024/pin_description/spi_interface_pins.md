# Description of SPI interface pins and communication protocol

**Source**: Page 28, Chunk 87  
**Category**: Description of SPI interface pins and communication protocol  
**Chunk Index**: 87

---

Table 16 SPI interface pins
SPI interface pin Description Communication direction
CS Chip Select (active low) MCU to ASIC
SCK Serial Clock MCU to ASIC
MOSI Master Out Slave In MCU to ASIC
MISO Master In Slave Out ASIC to MCU
SPI communication uses out-of-frame protocol, so each transfer has two phases. The first phase
contains the SPI command (request) and the data (response) of the previous command. The second
phase contains the next request and the response to the request of the first phase, see Figure 12. The
first response after reset is undefined and shall be discarded.
Product SPI block implements two different SPI protocol types. Both protocol types can be used during
operation by defining the SPI frame bit length.

---

**AI Reasoning**: The content primarily describes the SPI interface pins and their communication directions, which fits well under 'pin_description'. The filename captures the essence of the content, focusing on the SPI interface pins. This organization ensures easy access to pin-related information without excessive nesting.
