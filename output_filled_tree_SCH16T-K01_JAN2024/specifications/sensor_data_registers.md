# Register specifications for sensor data

**Source**: Page 37, Chunk 122  
**Category**: Register specifications for sensor data  
**Chunk Index**: 122

---

37 (53)
CONFIDENTIAL
Data Data Data Data
Adress 15h0000 15h0010 15h0020 15h0030
width width width width
4hD ACC_X2 20-bit STAT_ACC_Z 16-bit Reserved - SN_ID1 16-bit
4hE ACC_Y2 20-bit STAT_SYNC_ACTI 12-bit Reserved - SN_ID2 16-bit
VE
4hF ACC_Z2 20-bit STAT_INFO 9-bit Reserved - SN_ID3 16-bit
SPI frame bit D1/D0 is specified according to Safe SPI standard.
The sensor data bit D identifies if SPI response frame contains sensor data (i.e., identifies response

---

**AI Reasoning**: The content chunk provides detailed information about specific data registers related to sensor data, including addresses and bit widths. This fits well under 'specifications' as it details the technical specifications of the sensor's data registers.
