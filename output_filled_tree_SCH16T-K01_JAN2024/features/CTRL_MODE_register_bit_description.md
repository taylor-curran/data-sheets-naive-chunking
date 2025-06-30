# Register Bit Descriptions

**Source**: Page 49, Chunk 187  
**Category**: Register Bit Descriptions  
**Chunk Index**: 187

---

Table 71 CTRL_MODE register bit description
Reset
Bit Name Bit Description Bits
Value
Reserved Reserved [3:2] 2b00
EOI_CTRL End of Initialization, lock all R/W registers except soft reset control and SYS_TEST. This [1:1] 1b0
bit can only be set when there are no errors in common status.
EN_SENSOR Enable RATE and ACC measurement. Write bit to '1' according to start-up sequence. [0:0] 1b0
Reset
Bit Name Bit Description Bits

---

**AI Reasoning**: The content describes the bit settings and functions of the CTRL_MODE register, which is a feature of the hardware. It provides detailed information on how specific bits control the device's operation, making 'features' the most appropriate category. The filename captures the essence of the content by specifying the register and its bit description.
