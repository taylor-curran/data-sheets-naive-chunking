# Details about AXI interconnect registers and their functionality

**Source**: Page 117, Chunk 853  
**Category**: Details about AXI interconnect registers and their functionality  
**Chunk Index**: 853

---

RM0433 Memory and bus architecture
AXI interconnect - TARG x bus matrix functionality 2 register
(AXI_TARGx_FN_MOD2)
Address offset: 0x1024 + 0x1000 * x, where x = 1, 2 and 7
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
BYPAS
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. S_MER
GE
rw
Bits 31:1 Reserved, must be kept at reset value.
Bit 0 BYPASS_MERGE: Disable packing of beats to match the output data width. Unaligned
transactions are not realigned to the input data word boundary.
0: Normal operation
1: Disable packing
AXI interconnect - TARG x long burst functionality modification register
(AXI_TARGx_FN_MOD_LB)
Address offset: 0x102C + 0x1000 * x, where x = 1 and 2
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
FN_MO
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
D_LB
rw
Bits 31:1 Reserved, must be kept at reset value.
Bit 0 FN_MOD_LB: Controls burst breaking of long bursts
0: Long bursts can not be generated at the output of the ASIB
1: Long bursts can be generated at the output of the ASIB
RM0433 Rev 8 117/3353
128

---

**AI Reasoning**: The content describes specific registers related to the AXI interconnect, including their address offsets, reset values, and bit functionalities. This fits well under 'specifications' as it provides detailed technical specifications of the hardware components. The filename captures the essence of the content by focusing on the AXI interconnect registers.
