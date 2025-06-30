# Description of ACC_DCNT register bits and their function

**Source**: Page 40, Chunk 134  
**Category**: Description of ACC_DCNT register bits and their function  
**Chunk Index**: 134

---

Table 30 ACC_DCNT register bit description
Reset
Bit Name Bit Description Bits
Value
ACC_Z_DCNT 4-bit data counter for ACC_Z output. Data counter value is updated (+1) when a new [11:8] 4b0000
sample is available from corresponding RATE/ACC channel. When counter reaches
4d15, it rolls back to zero.
ACC_Y_DCNT 4-bit data counter for ACC_Y output. Data counter value is updated (+1) when a new [7:4] 4b0000
sample is available from corresponding RATE/ACC channel. When counter reaches
4d15, it rolls back to zero.
ACC_X_DCNT 4-bit data counter for ACC_X output Data counter value is updated (+1) when a new [3:0] 4b0000
sample is available from corresponding RATE/ACC channel. When counter reaches
4d15, it rolls back to zero.

---

**AI Reasoning**: The content provides detailed information about the ACC_DCNT register bits, which is a technical specification of the hardware. Placing it under 'specifications' makes it easy to find for those looking for technical details about register configurations. The filename captures the essence of the content by specifying the register and its description.
