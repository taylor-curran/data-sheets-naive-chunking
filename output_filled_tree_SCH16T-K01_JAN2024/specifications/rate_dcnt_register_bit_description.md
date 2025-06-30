# Description of RATE_DCNT register bits

**Source**: Page 40, Chunk 133  
**Category**: Description of RATE_DCNT register bits  
**Chunk Index**: 133

---

Table 29 RATE_DCNT register bit description
Reset
Bit Name Bit Description Bits
Value
RATE_Z_DCNT 4-bit data counter for RATE_Z output. Data counter value is updated (+1) when a new [11:8] 4b0000
sample is available from corresponding RATE/ACC channel. When counter reaches
4d15, it rolls back to zero.
RATE_Y_DCNT 4-bit data counter for RATE_Y output. Data counter value is updated (+1) when a new [7:4] 4b0000
sample is available from corresponding RATE/ACC channel. When counter reaches
4d15, it rolls back to zero.
RATE_X_DCNT 4-bit data counter for RATE_X output. Data counter value is updated (+1) when a new [3:0] 4b0000
sample is available from corresponding RATE/ACC channel. When counter reaches
4d15, it rolls back to zero.
Reset
Bit Name Bit Description Bits

---

**AI Reasoning**: The content describes the bit structure and functionality of the RATE_DCNT register, which is a technical specification of the hardware. Placing it under 'specifications' makes it easily accessible for users looking for detailed technical information about the register's operation.
