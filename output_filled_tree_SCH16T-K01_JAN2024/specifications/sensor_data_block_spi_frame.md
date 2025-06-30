# Details about the sensor data block and SPI frame format

**Source**: Page 37, Chunk 123  
**Category**: Details about the sensor data block and SPI frame format  
**Chunk Index**: 123

---

7.2 Sensor data block
SPI frame bit D1/D0 is specified according to Safe SPI standard.
The sensor data bit D identifies if SPI response frame contains sensor data (i.e., identifies response
frame format).
D=0: no sensor data, e.g., status data or read back of configuration data
D=1: sensor data
Register
Register Description R/RW Public addr

---

**AI Reasoning**: The content discusses the sensor data block and its relation to the SPI frame format, which fits under specifications as it provides technical details about how the sensor data is structured and communicated. Keeping it in 'specifications' ensures it is easily accessible for those looking for technical details.
