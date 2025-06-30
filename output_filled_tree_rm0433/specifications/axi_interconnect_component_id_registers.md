# Details about AXI interconnect component ID registers

**Source**: Page 115, Chunk 850  
**Category**: Details about AXI interconnect component ID registers  
**Chunk Index**: 850

---

RM0433 Memory and bus architecture
AXI interconnect - component ID1 register (AXI_COMP_ID_1)
Address offset: 0x1FF4
Reset value: 0x0000 00F0
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. CLASS[3:0] PREAMBLE[11:8]
r r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:4 CLASS[3:0]: Component class
0xF: Generic IP component class
Bits 3:0 PREAMBLE[11:8]: Preamble bits 8 to 11
0x0: Common ID value
AXI interconnect - component ID2 register (AXI_COMP_ID_2)
Address offset: 0x1FF8
Reset value: 0x0000 0005
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. PREAMBLE[19:12]
r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:0 PREAMBLE[19:12]: Preamble bits 12 to 19
0x05: Common ID value
RM0433 Rev 8 115/3353
128

---

**AI Reasoning**: The content provides specific details about the AXI interconnect component ID registers, including address offsets and reset values. This fits well under 'specifications' as it describes technical specifications of the hardware components. The filename captures the essence of the content by focusing on the AXI interconnect component ID registers.
