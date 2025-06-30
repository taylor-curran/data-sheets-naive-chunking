# Example of acceleration data conversion in different modes

**Source**: Page 38, Chunk 128  
**Category**: Example of acceleration data conversion in different modes  
**Chunk Index**: 128

---

7.2.2 Example of acceleration data conversion
Interpolated output of ACC Y is used as example. Data is in 2’s complement format.
16-bit mode
In 16-bit mode, default sensitivity is 200 LSB/(m/s2)
If ACC Y register (15h0005) read result is ACC Y= 80A00DC6h, content is converted to acceleration as
follows:
- 80Ah = 1 0 0 0000 0101 0b (contains D bit, address bits and first Status bit)
- 00DCh =0000 0000 1101 1100b (ACC Y register content)
- 00DCh in 2’s complement format = 220d
- Acceleration = 220 LSB/sensitivity = 220 LSB/ (200 LSB/(m/s2)) ≈ 1.1 m/s2
- 6h = CRC of 80A00DC0h
20-bit mode
In 20-bit mode, default sensitivity is 3200 LSB/(m/s2)
If ACC Y register (15h0005) read result is ACC Y= 80A0000DC0DBh, content is converted to
acceleration as follows:
- 80A00h = 1 0 0 0000 0101 0 0 00 0000 0b (contains D-bit, address-, status- and DCNT bits and one
empty bit)
- 00DC0h =0000 0000 1101 1100 0000b (ACC Y register content)
- 00DC0h in 2’s complement format = 3520d
- Acceleration= 3520 LSB/sensitivity = 3520 LSB/ (3200 LSB/(m/s2)) ≈ 1.1 m/s2
- DBh = CRC of 80A00DC000h
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides a detailed example of how acceleration data is converted from register values in both 16-bit and 20-bit modes. This fits well under 'specifications' as it details specific operational characteristics of the device. The filename captures the essence of the content, focusing on the example of data conversion.
