# Description of the STAT_RATE_COM register bits for gyroscope status

**Source**: Page 42, Chunk 146  
**Category**: Description of the STAT_RATE_COM register bits for gyroscope status  
**Chunk Index**: 146

---

Table 40 STAT_RATE_COM register bit description
Bit Name Bit Description Bits Normal operation value
RESERVED Reserved [15:8] 8b11111111
PRI_AGC_OK Gyro primary loop status [7:7] 1b1
GYRO_PRI_OK Gyro primary loop status [6:6] 1b1
PRI_START_OK Gyro primary loop start-up status [5:5] 1b1
GYRO_HV_OK Gyro High Voltage status [4:4] 1b1
RESERVED Reserved [3:3] 1b1
GYRO_SD_STS_OK Gyro Shield Detection Start-up Self-test status [2:2] 1b1
GYRO_BOND_STS_OK Gyro Bond wire Start-up Self-test status [1:1] 1b1
GYRO_STS_RDY_OK Gyro Start-up Self-test ready status flag [0:0] 1b1

---

**AI Reasoning**: The content provides detailed information about the bits in the STAT_RATE_COM register, which is related to the specifications of the gyroscope's status. Placing it under 'specifications' makes it easy to find for those looking for technical details about the gyroscope's operation.
