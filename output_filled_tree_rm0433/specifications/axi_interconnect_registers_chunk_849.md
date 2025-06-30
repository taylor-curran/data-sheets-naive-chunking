# Details about AXI interconnect peripheral and component ID registers

**Source**: Page 114, Chunk 849  
**Category**: Details about AXI interconnect peripheral and component ID registers  
**Chunk Index**: 849

---

Memory and bus architecture RM0433
AXI interconnect - peripheral ID3 register (AXI_PERIPH_ID_3)
Address offset: 0x1FEC
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. REV_AND[3:0] CUST_MOD_NUM[3:0]
r r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:4 REV_AND[3:0]: Customer version
0: None
Bits 3:0 CUST_MOD_NUM[3:0]: Customer modification
0: None
AXI interconnect - component ID0 register (AXI_COMP_ID_0)
Address offset: 0x1FF0
Reset value: 0x0000 000D
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. PREAMBLE[7:0]
r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:0 PREAMBLE7:0]: Preamble bits 0 to 7
0xD: Common ID value
114/3353 RM0433 Rev 8

---

**AI Reasoning**: The content describes specific registers within the AXI interconnect, including their address offsets, reset values, and bit definitions. This fits well under 'specifications' as it provides detailed technical information about the hardware's memory and bus architecture.
