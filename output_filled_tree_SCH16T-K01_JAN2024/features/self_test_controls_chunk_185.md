# Description of self-test control register bits

**Source**: Page 49, Chunk 185  
**Category**: Description of self-test control register bits  
**Chunk Index**: 185

---

Table 69 CTRL_ST register bit description
Reset
Bit Name Bit Description Bits
Value
Reserved Reserved [12:12] 1b0
RATE_Z_STC_CTRL Enable RATE_Z continuous self-test by writing bit to '0' [11:11] 1b1
RATE_Y_STC_CTRL Enable RATE_Y continuous self-test by writing bit to '0' [10:10] 1b1
RATE_X_STC_CTRL Enable RATE_X continuous self-test by writing bit to '0' [9:9] 1b1
ACC_Z_STC_MASK1 Mask ACC_Z continuous self-test flag (STC_N) by writing bit to '0' [8:8] 1b1
ACC_Y_STC_MASK1 Mask ACC_Y continuous self-test flag (STC_N) by writing bit to '0' [7:7] 1b1
ACC_X_STC_MASK1 Mask ACC_X continuous self-test flag (STC_N) by writing bit to '0' [6:6] 1b1
ACC_Z_STC_MASK2 Mask ACC_Z continuous self-test flag (STC_SDD) by writing bit to '0' [5:5] 1b1
ACC_Y_STC_MASK2 Mask ACC_Y continuous self-test flag (STC_SDD) by writing bit to '0' [4:4] 1b1
ACC_X_STC_MASK2 Mask ACC_X continuous self-test flag (STC_SDD) by writing bit to '0' [3:3] 1b1
ACC_STS_CTRL Enable ACC start-up self-test by writing bit to '0' [2:2] 1b1
TEMP_STS_CTRL Enable Temperature sensor Self-test by writing bit to '0' [1:1] 1b1
ACC_STS_REQ Request ACC start-up self-test by writing bit to '1'. Bit is set automatically to ‘0’ [0:0] 1b0
when test is over. ACC STS is performed automatically during start-up routine.

---

**AI Reasoning**: The content describes the self-test control register bits, which is a feature of the hardware. Placing it under 'features' makes it easily discoverable for users looking for information on specific functionalities of the device. The filename 'self_test_controls.md' succinctly captures the essence of the content.
