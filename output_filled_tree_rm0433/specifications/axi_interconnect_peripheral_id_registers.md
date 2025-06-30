# Details about AXI interconnect peripheral ID registers

**Source**: Page 113, Chunk 848  
**Category**: Details about AXI interconnect peripheral ID registers  
**Chunk Index**: 848

---

RM0433 Memory and bus architecture
AXI interconnect - peripheral ID1 register (AXI_PERIPH_ID_1)
Address offset: 0x1FE4
Reset value: 0x0000 00B4
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. JEP106ID[3:0] PARTNUM[11:8]
r r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:4 JEP106ID[3:0]: JEP106 identity bits 0 to 3
0xB: Arm® JEDEC code
Bits 3:0 PARTNUM[11:8]: Peripheral part number bits 8 to 11
0x4: Part number = 0x400
AXI interconnect - peripheral ID2 register (AXI_PERIPH_ID_2)
Address offset: 0x1FE8
Reset value: 0x0000 002B
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. REVISION[3:0] JEDEC JEP106ID[6:4]
r r r
Bits 7:4 REVISION[3:0]: Peripheral revision number
0x2: r0p2
Bit 3 JEDEC: JEP106 code flag
0x1: JEDEC allocated code
Bits 2:0 JEP106ID[6:4]: JEP106 Identity bits 4 to 6
0x3: Arm® JEDEC code
RM0433 Rev 8 113/3353
128

---

**AI Reasoning**: The content provides detailed specifications of the AXI interconnect peripheral ID registers, including address offsets, reset values, and bit definitions. This fits well under a 'specifications' category, which is broad enough to encompass various technical details. The filename captures the essence of the content, focusing on the specific registers discussed.
