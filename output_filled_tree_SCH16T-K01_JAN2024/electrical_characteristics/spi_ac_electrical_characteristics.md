# SPI AC electrical characteristics

**Source**: Page 16, Chunk 55  
**Category**: SPI AC electrical characteristics  
**Chunk Index**: 55

---

16 (53)
Table 12 SPI AC electrical characteristics
Title Remark Symbol Min Max Unit
SCK Operating 0.095 10.5 MHz
Frequency
MISO data valid time A 40 ns
(CS)
MISO data valid time B 32 ns
(SCK)
MOSI data hold time C 20 ns
MISO rise/fall time MISO rise/fall time is not defined during transition between high D 2 9 ns
impedance and active mode
MISO data disable lag E 50 ns
time
MOSI data setup time F 10 ns
SCK disable lead time 1 10 ns
SCK enable lead time 2 40 ns
SCK rise and fall time 3 2 9
SCK high time 4 37 ns
SCK low time 5 37 ns
SCK enable lag time 6 20 ns
SCK disable lag time 7 10 ns
Sequential transfer In case of MOSI Write commands (RW=1) 9 750 ns
delay
Sequential transfer In case of MOSI Read commands (RW=0) 9 450 ns
delay
MOSI rise and fall time 10 2 9 ns
MOSI data setup time Setup time of MOSI before the rising edge of SCK 11 5 ns
MISO data hold time 12 X ns
MOSI valid time 13 10 ns
CS rise and fall time 10 2 9 ns
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content chunk provides detailed specifications related to the SPI AC electrical characteristics, including timing parameters and signal definitions. This fits well under a broad category of 'electrical_characteristics' as it deals with the electrical behavior of the SPI interface. The filename captures the essence of the content by specifying the focus on SPI AC characteristics.
