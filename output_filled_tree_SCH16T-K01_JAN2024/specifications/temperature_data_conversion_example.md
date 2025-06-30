# Example of temperature data conversion in 16-bit and 20-bit modes

**Source**: Page 39, Chunk 129  
**Category**: Example of temperature data conversion in 16-bit and 20-bit modes  
**Chunk Index**: 129

---

39 (53)
CONFIDENTIAL
7.2.3 Example of temperature data conversion
16-bit mode
Temperature signal sensitivity is 100 LSB/°C
If TEMP register (15h0010) read result is TEMP = 82000DC5h, content is converted to temperature as
follows:
- 820h = 1 0 0 0001 0000 0b (contains D bit, address bits and first Status bit)
- 00DCh =0000 0000 1101 1100b (TEMP register content)
- 00DCh in 2’s complement format = 220d
- Temperature= 220 LSB/sensitivity = 220 LSB/ (100 LSB/°C) = 2.2°C
- 5h = CRC of 82000DC0h
20-bit mode
The temperature data is always 16-bit wide. In 20-bit mode, this needs to be taken into account. The
user has two options:
from 1 to 0. Then, convert TEMP data as explained in 16-bit mode.

---

**AI Reasoning**: The content provides a detailed example of how temperature data is converted from register readings in different modes. This fits well under 'specifications' as it describes the operational specifics of the hardware. The filename captures the essence of the content, making it easily discoverable.
