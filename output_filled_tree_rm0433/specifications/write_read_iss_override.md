# Register configuration for ASIB write and read issuing capabilities

**Source**: Page 120, Chunk 859  
**Category**: Register configuration for ASIB write and read issuing capabilities  
**Chunk Index**: 859

---

WRITE READ
_ISS_ _ISS_
Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res. Res.
OVERR OVERR
IDE IDE
rw rw
Bits 31:2 Reserved, must be kept at reset value.
Bit 1 WRITE_ISS_OVERRIDE: Override ASIB write issuing capability
0: Normal issuing capability
1: Force issuing capability to 1
Bit 0 READ_ISS_OVERRIDE: Override ASIB read issuing capability
0: Normal issuing capability
1: Force issuing capability to 1
120/3353 RM0433 Rev 8

---

**AI Reasoning**: The content describes specific register bits related to the configuration of write and read issuing capabilities in the ASIB. This fits well under 'specifications' as it details how certain functionalities are controlled at the register level. The filename captures the essence of the content by highlighting the main focus: the WRITE_ISS_OVERRIDE and READ_ISS_OVERRIDE bits.
