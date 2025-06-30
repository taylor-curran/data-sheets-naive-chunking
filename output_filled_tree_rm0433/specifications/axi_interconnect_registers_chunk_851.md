# Details about AXI interconnect registers and their configurations

**Source**: Page 116, Chunk 851  
**Category**: Details about AXI interconnect registers and their configurations  
**Chunk Index**: 851

---

Memory and bus architecture RM0433
AXI interconnect - component ID3 register (AXI_COMP_ID_3)
Address offset: 0x1FFC
Reset value: 0x0000 00B1
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. PREAMBLE[27:20]
r
Bits 31:8 Reserved, must be kept at reset value.
Bits 7:0 PREAMBLE[27:20]: Preamble bits 20 to 27
0xB1: Common ID value
AXI interconnect - TARG x bus matrix issuing functionality register
(AXI_TARGx_FN_MOD_ISS_BM)
Address offset: 0x1008 + 0x1000 * x, where x = 1 to 7
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0

---

**AI Reasoning**: The content is technical and specific to the configuration of AXI interconnect registers, which fits well under 'specifications'. The filename captures the essence of the content, focusing on the AXI interconnect registers, making it easily discoverable.
