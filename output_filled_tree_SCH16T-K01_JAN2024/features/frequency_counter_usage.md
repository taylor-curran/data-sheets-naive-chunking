# Explanation of frequency counter functionality and usage

**Source**: Page 27, Chunk 84  
**Category**: Explanation of frequency counter functionality and usage  
**Chunk Index**: 84

---

5.4.6 Frequency counter
Using frequency counter, user can acquire accurate clock information from component internal MCLK
via SPI. The value of frequency counter register is increased by one with every 16th rising edge of
master clock.
The data counter value can be combined with the frequency counter value to calculate the exact time
stamp of a sample when the MCU clock of the host system is used as reference. This combination is

---

**AI Reasoning**: The content describes the functionality and usage of a frequency counter, which is a feature of the hardware. Placing it under 'features' makes it easily discoverable for users looking for specific functionalities. The filename captures the essence of the content by focusing on the frequency counter's usage.
