# Overview of sensor control block registers and their functions

**Source**: Page 45, Chunk 160  
**Category**: Overview of sensor control block registers and their functions  
**Chunk Index**: 160

---

45 (53)
CONFIDENTIAL
7.4 Sensor control block
Table 52 Sensor control block register overview
Register Name Register Description R/RW Public addr
Reserved Reserved RW 15h0021, D0
CTRL_FILT_RATE RATE_XYZ Filter settings. Common filter for each axis X1/X2, Y1/Y2, Z1/Z2. RW 15h0025, D0
CTRL_FILT_ACC12 ACC filter setting. Common filter for each ACC axis X1/X2, Y1/Y2, Z1/Z2. RW 15h0026, D0
CTRL_FILT_ACC3 Filter setting for ACC_X3, ACC_Y3 and ACC_Z3. RW 15h0027, D0
CTRL_RATE Settings for Gyro post-processing decimation ratio and dynamic range RW 15h0028, D0
CTRL_ACC12 Settings for ACC_X12, ACC_Y12, ACC_Z12 post-processing decimation RW 15h0029, D0
ratio and dynamic range
CTRL_ACC3 Settings for ACC_X3, ACC_Y3, ACC_Z3 post-processing shift dynamic RW 15h002A, D0
range
Reserved Reserved RW 15h002B, D0
Reserved Reserved RW 15h002C, D0
Reserved Reserved RW 15h002D, D0
Reserved Reserved RW 15h002E, D0
CTRL_USER_IF User controls for SYNC, Data Ready, Strength of SPI PD/PU, slew rate ctrl, RW 15h0033, D0
hi-speed
CTRL_ST Self-test controls (enable ST and/or request STS) RW 15h0034, D0
CTRL_MODE Test mode, EOI, EN_SENSOR RW 15h0035, D0
CTRL_RESET SPI soft reset command RW 15h0036, D0
SYS_TEST Empty register for testing read/write access RW 15h0037, D0

---

**AI Reasoning**: The content provides detailed information about the sensor control block registers, including their names, descriptions, and addresses. This fits well under 'specifications' as it specifies the technical details of the sensor control block. The filename captures the essence of the content by highlighting the focus on registers within the sensor control block.
