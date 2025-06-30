# Details about the AXI interconnect functionality modification register

**Source**: Page 118, Chunk 855  
**Category**: Details about the AXI interconnect functionality modification register  
**Chunk Index**: 855

---

WRITE READ
_ISS_ _ISS_
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
OVERR OVERR
IDE IDE
rw rw
Bits 31:2 Reserved, must be kept at reset value.
Bit 1 WRITE_ISS_OVERRIDE: Override AMIB write issuing capability
0: Normal issuing capability
1: Force issuing capability to 1
Bit 0 READ_ISS_OVERRIDE: Override AMIB read issuing capability
0: Normal issuing capability
1: Force issuing capability to 1
AXI interconnect - INI x functionality modification 2 register
(AXI_INIx_FN_MOD2)
Address offset: 0x41024 + 0x1000 * x, where x = 1 and 3
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
BYPAS
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. S_MER
GE
rw
Bits 31:1 Reserved, must be kept at reset value.
Bit 0 BYPASS_MERGE: Disables alteration of transactions by the up-sizer unless required by the
protocol
0: Normal operation
1: Transactions pass through unaltered where allowed
118/3353 RM0433 Rev 8

---

**AI Reasoning**: The content describes specific register settings and functionalities related to the AXI interconnect, which fits well under 'specifications'. The filename captures the essence of the register being discussed, making it easy to locate for users interested in register specifications.
