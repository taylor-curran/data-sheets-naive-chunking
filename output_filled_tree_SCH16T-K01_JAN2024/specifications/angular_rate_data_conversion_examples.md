# Examples of converting angular rate data from sensor readings

**Source**: Page 38, Chunk 127  
**Category**: Examples of converting angular rate data from sensor readings  
**Chunk Index**: 127

---

38 (53)
CONFIDENTIAL
7.2.1 Example of angular rate data conversion
Interpolated output of Rate X is used as example. Data is in 2’s complement format.
16-bit mode
In 16-bit mode, default sensitivity is 100 LSB/(°/s)
If Rate X register (15h0001) read result is Rate X = 802FFE07h, content is converted to angular rate as
follows:
- 802h = 1 0 0 0000 0001 0b (contains D bit, address bits and first Status bit)
- FFE0h = 1111 1111 1110 0000b (Rate X register content)
- FFE0h in 2’s complement format = -32d
- Angular rate = -32 LSB/sensitivity = -32 LSB/ (100 LSB/(°/s)) = -0.32 °/s
- 7h = CRC of 802FFE0h
20-bit mode
In 20-bit mode, default sensitivity is 1600 LSB/(°/s)
If Rate X register (15h0001) read result is Rate X =80200FFE00ADh, content is converted to angular
rate as follows:
- 80200h = 1 0 0 0000 0001 0 0 00 0000 0b (contains D-bit, address-, status- and DCNT bits and one
empty bit)
- FFE00h = 1111 1111 1110 0000 0000b (Rate X register content)
- FFE00h in 2’s complement format = -512d
- Angular rate = -512 LSB/sensitivity = -512 LSB/ (1600 LSB/(°/s)) = -0.32 °/s
- ADh = CRC of 80200FFE00h
Interpolated output of ACC Y is used as example. Data is in 2’s complement format.
16-bit mode

---

**AI Reasoning**: The content provides detailed examples of converting sensor data into angular rate values, which fits well under 'specifications' as it describes how the device's data is interpreted. The filename captures the essence of the content by highlighting the focus on data conversion examples.
