# Filter settings and register details

**Source**: Page 45, Chunk 161  
**Category**: Filter settings and register details  
**Chunk Index**: 161

---

7.4.1 Filter settings
Table 53 Filter setting registers
Register Name Register Description R/RW Public addr
CTRL_FILT_RATE RATE_XYZ Filter settings. Common filter for each axis X1/X2, Y1/Y2, Z1/Z2. RW 15h0025, D0
CTRL_FILT_ACC12 ACC filter setting. Common filter for each ACC axis X1/X2, Y1/Y2, Z1/Z2. RW 15h0026, D0
CTRL_FILT_ACC3 Filter setting for ACC_X3, ACC_Y3 and ACC_Z3. RW 15h0027, D0
For detailed Filter characteristics, please refer Table 9 SCH16T Filter characteristics
Name Bits Nominal Cut-off Frequency (-3dB)
LPF0 '000' 68 Hz (default)

---

**AI Reasoning**: The content chunk provides detailed information about filter settings and associated registers, which are technical specifications of the hardware. Placing it under 'specifications' makes it easily discoverable for users looking for technical details. The filename captures the essence of the content by highlighting the focus on filter settings and registers.
