# Overview of sensor status block registers and descriptions

**Source**: Page 39, Chunk 131  
**Category**: Overview of sensor status block registers and descriptions  
**Chunk Index**: 131

---

7.3 Sensor status block
Table 27 Overview of sensor status block
Register Name Register Description R/RW Public addr
RATE_DCNT Data counter for RATE_XYZ2 R 15h0011, D0
ACC_DCNT Data counter for ACC_XYZ R 15h0012, D0
FREQ_CNTR Frequency / sample time counter R 15h0013, D0
STAT_SUM Status summary for non-saturation related flags R 15h0014, D0
STAT_SUM_SAT Status summary for saturation flags R 15h0015, D0
STAT_COM Common Status flags, incl. TEMP, 1st level status register R 15h0016, D0
STAT_RATE_COM Common gyro status flags (primary channel), 1st level status register R 15h0017, D0
STAT_RATE_X RATE_X status flags, 1st level status register R 15h0018, D0
STAT_RATE_Y RATE_Y status flags, 1st level status register R 15h0019, D0
STAT_RATE_Z RATE_Z status flags, 1st level status register R 15h001A, D0
STAT_ACC_X ACC_X status flags, 1st level status register R 15h001B, D0
STAT_ACC_Y ACC_Y status flags, 1st level status register R 15h001C, D0
STAT_ACC_Z ACC_Z status flags, 1st level status register R 15h001D, D0
STAT_SYNC_ACTIVE Status of SYNC on each channel R 15h001E, D0
STAT_INFO Low power mode indications R 15h001F, D0
Reserved Reserved R 15h0020, D0
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides detailed information about the sensor status block, including register names, descriptions, and addresses. This fits well under 'specifications' as it specifies the technical details of the sensor's status block.
