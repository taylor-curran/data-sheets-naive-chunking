# Summary of supported features for SafeSPI v2.0 in SCH16T

**Source**: Page 28, Chunk 89  
**Category**: Summary of supported features for SafeSPI v2.0 in SCH16T  
**Chunk Index**: 89

---

SPI block does not implement the complete SafeSPI v2.0 specification. Summary of supported features
can be seen in table below. For Safe SPI standard, please refer to www.SafeSPI.org
Table 17 SCH16T supported features of SafeSPI v2.0
Supported feature Description
<48/32oof> Block receives and transmits 32-bit and 48-bit Out-of-frame SPI frames. In-frame protocols are not
supported.
<FrTyp> MOSI frame width is defined by received frame length. Frame is effective only if width is 32-bits or
48-bits and the CRC is valid.
<SelBitWidthByAdr > Next MISO frame width is decided by <FrTyp>
<Sel4SlaveByAdrPin> Two MSB address bits can be used to select one of four slaves when one CS signal pin is in use.
Slave compares the two MSBs to a reference value defined by two input pins.
<Sel4SlaveByAdrNVM> Two MSB address bits can be used to select one of four slaves when one CS signal pin is in use.
Slave compares the two MSBs to a reference value defined by a NVM programmed value. Factory
use only.
<FixedSensorFrame> Frame content is well defined and fixed.
<CLWide> Wide range for “total signal load capacitance”
<DCnt> Block updates a wrapping 4-bit sample counter each time new sensor data is generated.
<IDS> Internal Data Status field includes additional status information for sensor data.
<CAP> Not implemented and replaced with fixed value.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content chunk provides a summary of the supported features of the SafeSPI v2.0 protocol for the SCH16T device. It fits well under the 'features' category as it details specific capabilities and limitations of the SPI block implementation. The filename captures the essence of the content by highlighting the focus on SafeSPI v2.0 supported features.
