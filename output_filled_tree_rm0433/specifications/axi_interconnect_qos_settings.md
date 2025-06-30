# AXI interconnect QoS and override settings

**Source**: Page 119, Chunk 857  
**Category**: AXI interconnect QoS and override settings  
**Chunk Index**: 857

---

WR_IN RD_IN
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. C_OVE C_OVE
RRIDE RRIDE
rw rw
Bits 31:2 Reserved, must be kept at reset value.
Bit 1 WR_INC_OVERRIDE: Converts all AHB-Lite read transactions to a series of single beat AXI
transactions.
0: Override disabled
1: Override enabled
Bit 0 RD_INC_OVERRIDE: Converts all AHB-Lite write transactions to a series of single beat AXI
transactions, and each AHB-Lite write beat is acknowledged with the AXI buffered write
response.
0: Override disabled
1: Override enabled
AXI interconnect - INI x read QoS register (AXI_INIx_READ_QOS)
Address offset: 0x41100 + 0x1000 * x, where x = 1 to 76
Reset value: 0x0000 0000
31 30 29 28 27 26 25 24 23 22 21 20 19 18 17 16
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
15 14 13 12 11 10 9 8 7 6 5 4 3 2 1 0
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. AR_QOS[3:0]
rw
Bits 31:4 Reserved, must be kept at reset value.
Bits 3:0 AR_QOS[3:0]: Read channel QoS setting
0x0: Lowest priority
0xF: Highest priority
RM0433 Rev 8 119/3353
128

---

**AI Reasoning**: The content describes specific register settings related to AXI interconnect QoS and override functionalities, which are technical specifications of the microcontroller. Placing it under 'specifications' makes it easily discoverable for users looking for detailed technical information. The filename captures the essence of the content by highlighting the main topics: AXI interconnect and QoS settings.
