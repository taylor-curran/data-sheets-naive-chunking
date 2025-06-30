# DC characteristics of SPI I/O pins for SCH16T sensor

**Source**: Page 15, Chunk 53  
**Category**: DC characteristics of SPI I/O pins for SCH16T sensor  
**Chunk Index**: 53

---

Table 11 SPI DC characteristics
Title Symbol Min Max Unit
SPI Voltage Level VIO 1.7 3.6 V
Input High Voltage VIH 0.7*VIO VIO V
Input Low Voltage VIL 0 0.3*VIO V
Input Voltage Hysteresis VHYST 0.1*VIO V
Input/Output Capacitance CIO 10 pF
Total MISO load capacitance, <Wide> range CLWIDE 10 100 pF
Input pull-down resistance, strong (default) RPD 60 140 kOhm
Input pull-up resistance, strong (default) RPU 60 140 kOhm
Input pull-down/pull-up resistance, weak (option) RPD/RPU 200 400 kOhm
Output leakage current in case MISO is in high impedance (tri-state) ILEAK -10 10 µA
condition

---

**AI Reasoning**: The content provides detailed DC electrical characteristics for the SPI interface of the SCH16T sensor, which fits well under 'electrical_characteristics'. The filename 'spi_dc_characteristics.md' succinctly captures the essence of the content, making it easily discoverable.
