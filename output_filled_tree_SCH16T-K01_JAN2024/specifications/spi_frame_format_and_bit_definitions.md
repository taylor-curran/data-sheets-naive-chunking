# SPI frame format and bit definitions

**Source**: Page 29, Chunk 92  
**Category**: SPI frame format and bit definitions  
**Chunk Index**: 92

---

Figure 14 SPI frame format for 48-bit and 32-bit frames
Table 18 SPI bit definitions
SYMBOL DESCRIPTION
D D=1 condition:
Gyro data register read
ACC data register read
Temperature data register read
D=0 condition:
Any other register than listed above is read
TA Defines the Target Address in SCH16T.
TA[9:8] bits are used as Chip Select information, and thus they are not part of the effective address.
TA[7:0] are used as effective address within the chip.
SA Contains the Source Address. It has the same content as TA.
RW Read/write access selector. Read is selected with 0 and write with 1.
FT (FrTyp) Frame Type for next MISO frame: 0 for SPI32BF, 1 for SPI48BF. MOSI frame width is defined by the MOSI frame
itself, hence this field should match the next incoming MOSI frame since out-of-frame responses are in use.
AE Reserved. Bits shall be ignored.
DATAI MOSI line input data from SPI host. This field is 20-bits wide for SPI48BF and 16-bits for SPI32BF.
SENSOR MISO line sensor type output data towards SPI host.
INFO MISO line non-sensor type output data towards SPI host. This field is 20-bits wide for SPI48BF and 16-bits for
SPI32BF. 20-bit data is clipped from LSB end to 16-bit with SPI32BF, i.e. data is MSB aligned.
* Unused field that is ignored for receive and set to all-zeros for transmit.
S1:0, S1, Sensor status indication.
S0
CE Command Error indication. SCH16T reports only semantically invalid frame content using this field. SPI protocol
level errors are indicated with High-Z on MISO pin.
IDS Internal Data Status indication. SCH16T uses this field to indicate common cause error. This is redundant, more
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content focuses on the SPI frame format and the definitions of various bits within the SPI communication protocol for the SCH16T device. This is a technical specification detailing how data is structured and interpreted in SPI communication, making 'specifications' the most appropriate category. The filename captures the essence of the content by highlighting both the frame format and bit definitions.
