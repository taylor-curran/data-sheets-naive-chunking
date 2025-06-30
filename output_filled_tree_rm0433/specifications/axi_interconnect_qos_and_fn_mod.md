# Details about AXI interconnect QoS and functionality modification registers

**Source**: Page 120, Chunk 858  
**Category**: Details about AXI interconnect QoS and functionality modification registers  
**Chunk Index**: 858

---

Memory and bus architecture RM0433
AXI interconnect - INI x write QoS register (AXI_INIx_WRITE_QOS)
Address offset: 0x41104 + 0x1000 * x, where x = 1 to 76
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. AW_QOS[3:0]
rw
Bits 31:4 Reserved, must be kept at reset value.
Bits 3:0 AW_QOS[3:0]: Write channel QoS setting
0x0: Lowest priority
0xF: Highest priority
AXI interconnect - INI x issuing functionality modification register
(AXI_INIx_FN_MOD)
Address offset: 0x41108 + 0x1000 * x, where x = 1 to 76
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0

---

**AI Reasoning**: The content is technical and related to the configuration of AXI interconnect registers, which fits well under 'specifications'. The filename captures the essence of the content, focusing on the QoS and functionality modification aspects. This organization ensures easy access and understanding of the register specifications.
