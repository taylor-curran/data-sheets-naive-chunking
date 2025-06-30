# Register bit description for accelerometer X axis status

**Source**: Page 43, Chunk 153  
**Category**: Register bit description for accelerometer X axis status  
**Chunk Index**: 153

---

Table 46 STAT_ACC_X register bit description
Normal operation
Bit Name Bit Description Bits
value
RESERVED Reserved [15:11] 5b11111
ACC_X3_SAT_OK ACC_X3 output saturation. [10:10] 1b1
ACC_X_DEC_SAT_OK Decimated ACC (X2) output saturation. [9:9] 1b1
ACC_X_INTP_SAT_OK Interpolated ACC (X1) output saturation. [8:8] 1b1
ACC_X_STC_DIG_OK Accelerometer X Axis Continuous Self-test status 4 [7:7] 1b1
ACC_X_STC_TCAP_OK Accelerometer X Axis Test-Cap Continuous Self-test status [6:6] 1b1
ACC_X_STC_SDD_OK Accelerometer X Axis Continuous Self-test status 2 [5:5] 1b1
ACC_X_STC_N_OK Accelerometer X Axis Tone Continuous Self-test status [4:4] 1b1
RESERVED Reserved [3:3] 1b1
ACC_X_SD_STS_OK Accelerometer X Axis Shield Detection Start-up Self-test [2:2] 1b1
status
ACC_X_STS_OK Accelerometer X Axis Start-up Self-test status [1:1] 1b1
ACC_X_STS_RDY_OK Accelerometer X Axis Start-up Self-test ready [0:0] 1b1
Normal operation
Bit Name Bit Description Bits

---

**AI Reasoning**: The content describes the bit configuration and status indicators for the STAT_ACC_X register, which is related to the features and functionalities of the hardware. Placing it under 'features' makes it easily discoverable for those looking into specific functionalities or operational details of the device.
