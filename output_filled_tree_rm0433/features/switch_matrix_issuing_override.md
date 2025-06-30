# Switch matrix issuing override settings

**Source**: Page 116, Chunk 852  
**Category**: Switch matrix issuing override settings  
**Chunk Index**: 852

---

WRITE READ
_ISS_ _ISS_
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
OVERR OVERR
IDE IDE
rw rw
Bits 31:2 Reserved, must be kept at reset value.
Bit 1 WRITE_ISS_OVERRIDE: Switch matrix write issuing override for target
0: Normal issuing capability
1: Set switch matrix write issuing capability to 1
Bit 0 READ_ISS_OVERRIDE: Switch matrix read issuing override for target
0: Normal issuing capability
1: Set switch matrix read issuing capability to 1
116/3353 RM0433 Rev 8

---

**AI Reasoning**: The content describes specific settings related to the switch matrix issuing override, which is a feature of the microcontroller. Placing it under 'features' makes it easily discoverable for users looking for specific functionalities or settings of the device.
