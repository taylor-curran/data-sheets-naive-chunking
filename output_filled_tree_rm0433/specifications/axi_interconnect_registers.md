# Details about AXI interconnect registers including peripheral ID registers

**Source**: Page 112, Chunk 847  
**Category**: Details about AXI interconnect registers including peripheral ID registers  
**Chunk Index**: 847

---

Memory and bus architecture RM0433
2.2.4 AXI interconnect registers
AXI interconnect - peripheral ID4 register (AXI_PERIPH_ID_4)
Address offset: 0x1FD0
Reset value: 0x0000 0004
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. 4KCOUNT[3:0] JEP106CON[3:0]
r r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:4 4KCOUNT[3:0]: Register file size
0x0: N/A
Bits 3:0 JEP106CON[3:0]: JEP106 continuation code
0x4: Arm®
AXI interconnect - peripheral ID0 register (AXI_PERIPH_ID_0)
Address offset: 0x1FE0
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. PARTNUM[7:0]
r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:0 PARTNUM[7:0]: Peripheral part number bits 0 to 7
0x00: Part number = 0x400
112/3353 RM0433 Rev 8

---

**AI Reasoning**: The content provides detailed specifications of AXI interconnect registers, which are part of the hardware specifications. A shallow directory under 'specifications' ensures easy access and aligns with the nature of the content, which is technical and specific to register details.
