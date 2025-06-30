# Description of the STAT_ACC_Z register bits and their functions

**Source**: Page 44, Chunk 156  
**Category**: Description of the STAT_ACC_Z register bits and their functions  
**Chunk Index**: 156

---

Table 48 STAT_ACC_Z register bit description
Normal operation
Bit Name Bit Description Bits
value
RESERVED Reserved [15:11] 5b11111
ACC_Z3_SAT_OK ACC_Z3 output saturation. [10:10] 1b1
ACC_Z_DEC_SAT_OK Decimated ACC (Z2) output saturation. [9:9] 1b1
ACC_Z_INTP_SAT_OK Interpolated ACC (Z1) output saturation. [8:8] 1b1
ACC_Z_STC_DIG_OK Accelerometer Z Axis Continuous Self-test status 4 [7:7] 1b1
ACC_Z_STC_TCAP_OK Accelerometer Z Axis Test-Cap Continuous Self-test status [6:6] 1b1
ACC_Z_STC_SDD_OK Accelerometer Z Axis Continuous Self-test status 2 [5:5] 1b1
ACC_Z_STC_N_OK Accelerometer Z Axis Tone Continuous Self-test status [4:4] 1b1
RESERVED Reserved [3:3] 1b1
ACC_Z_SD_STS_OK Accelerometer Z Axis Shield Detection Start-up Self-test [2:2] 1b1
status
ACC_Z_STS_OK Accelerometer Z Axis Start-up Self-test status [1:1] 1b1
ACC_Z_STS_RDY_OK Accelerometer Z Axis Start-up Self-test ready [0:0] 1b1

---

**AI Reasoning**: The content provides detailed information about the STAT_ACC_Z register bits, which is a technical specification of the hardware. Placing it under 'specifications' makes it easy to find for those looking for detailed register information. The filename captures the essence of the content by specifying the register and its description.
