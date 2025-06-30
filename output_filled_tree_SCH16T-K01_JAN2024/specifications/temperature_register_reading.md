# Instructions for reading and converting temperature register data

**Source**: Page 39, Chunk 130  
**Category**: Instructions for reading and converting temperature register data  
**Chunk Index**: 130

---

1. Change frame type for temperature register read to 32-bit by changing FT bit of previous MOSI frame
from 1 to 0. Then, convert TEMP data as explained in 16-bit mode.
2. Read TEMP register in 20-bit mode. As data is only 16-bits wide, the remaining LSBs will be all
zeroes and they need to be discarded. After that, register content can be converted in similar manner as
explained in 16-bit mode.
If TEMP register (15h0010) read result is TEMP = 8200000DC0EAh, content is converted to
temperature (°C) as follows:
- 82000h = 1 0 0 0001 0000 0 0 00 0000 0b (contains D-bit, address-, status- and DCNT bits and one
empty bit)
- Discard last byte (0h).
- 00DCh =0000 0000 1101 1100b (TEMP register content)
- 00DCh in 2’s complement format = 220d
- Temperature= 220 LSB/sensitivity = 220 LSB/ (100 LSB/°C) = 2.2°C
- EAh = CRC of 82000DC000h

---

**AI Reasoning**: The content provides detailed instructions on how to read and convert data from the temperature register in different modes. This is a technical specification related to the operation of the hardware, making 'specifications' the most appropriate category. The filename captures the essence of the content, focusing on the process of reading and interpreting temperature data.
