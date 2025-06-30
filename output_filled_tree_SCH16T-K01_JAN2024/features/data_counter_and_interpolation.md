# Description of data counter and interpolation features

**Source**: Page 24, Chunk 72  
**Category**: Description of data counter and interpolation features  
**Chunk Index**: 72

---

24 (53)
CONFIDENTIAL
Feature Use case Value
- Data is updating
- Every wanted sample has been acquired
- The same sample has not been read twice
Data counter with Special case. Recommended if integration - Data counter together with frequency counter
frequency counter operation is performed to sensor data and can be used for more accurate integration.
timing uncertainty or data jitter of the
interpolated data do not fulfill the system
accuracy requirements.
SYNC and DRY (Data Ready) are implemented on a single hardware pin. Therefore, simultaneous use
of these functions is not possible. Controlling the behavior of SYNC and DRY is explained in chapter
7.4.
The purpose of interpolation is to minimize time uncertainty (sampling jitter) by increasing artificially the
internal sample rate. The natural output data rate of all data outputs is F_PRIM/2, which is 11.8 kHz

---

**AI Reasoning**: The content primarily discusses features related to data counting and interpolation, including their use cases and limitations. It fits well under a 'features' category, and the filename captures the essence of the discussed functionalities.
