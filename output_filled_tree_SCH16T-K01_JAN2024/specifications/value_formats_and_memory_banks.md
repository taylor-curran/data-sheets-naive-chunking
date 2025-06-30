# Value formats and memory bank addresses

**Source**: Page 36, Chunk 119  
**Category**: Value formats and memory bank addresses  
**Chunk Index**: 119

---

Table 24 Value formats
Decimal 5-bit decimal 5-bit signed hex 5-bit binary
13 13d 0Dh 5b01101
-13 -13d 13h 5b10011
All essential register content of SCH16T ASIC is mirrored to public memory banks listed below.
15h0000
15h0010
15h0020
15h0030
Detailed register content is explained in the next chapter. register address is a 4-bit offset within a
memory bank. final public address is formed by adding address offset to public bank address, for
example:
STAT_SUM register:
- Bank address: 15h0010
- Address offset 4h4
- Public Address: 15h0010 + 4h4 = 15h0014
Memory banks, address offsets and data widths can be seen in table below.
Green: Data registers

---

**AI Reasoning**: The content primarily discusses the formats of values and how register content is mirrored to memory banks, which fits under specifications as it details technical aspects of the hardware's operation.
