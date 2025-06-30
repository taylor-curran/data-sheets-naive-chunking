# Detailed description of CTRL_USER_IF register bits and their functions

**Source**: Page 48, Chunk 183  
**Category**: Detailed description of CTRL_USER_IF register bits and their functions  
**Chunk Index**: 183

---

01 - 1.8 V+/-8%
FTREE_TDEL Typical delay time of 1st level status clearance. When user reads data register, the [13:12] 2b10
associated 1st level status register is cleared after TDEL.
00 - 0.078 ms
01 - 0.625 ms
10 - 2.5 ms (default)
11 – 5 ms
SYNC_POL SYNC polarity control. [11:11] 1b0
0 - high active (rising edge) (default)
1 - low active (falling edge).
SYNC_TOC_TH SYNC time-out counter control. Counter starts to increase value after rising edge of [10:9] 2b00
SYNC_DRY. When counter reaches threshold value selected by SYNC_TOC_TH,
data collection is restarted. Counter is reset by falling edge of SYNC_DRY.
00 - 2^15 x MCLK (1.275...1.448 ms)
01 - 2^16 x MCLK (2.550...2.896 ms)
10 - 2^17 x MCLK (5.100...5.792 ms)
11 - 2^18 x MCLK (10.199...11.584 ms)
SYNC_DEC_EN Enables data freezing for Decimated output registers and their corresponding data [8:8] 1b0
counter registers. Can be set both simultaneously and separately with
SYNC_INTP_EN. If user enables SYNC and Data ready simultaneously, Data ready
takes priority.
0 - Disable
1 - Enable
SYNC_INTP_EN Enables data freezing for interpolated output registers and their corresponding data [7:7] 1b0
counter registers. Can be set both simultaneously and separately with
SYNC_DEC_EN. If user enables SYNC and Data ready simultaneously, Data ready
takes priority.
0 - Disable
1 - Enable
DRY_POL Data Ready polarity control. [6:6] 1b0
0 - high active (default)
1 - low active
DRY_DRV_EN Enables Data ready function. Writing this bit to 1 disables SYNC function, as they [5:5] 1b0
cannot be used simultaneously due to shared I/O pin.
1 - DRY buffer enabled
0 - DRY buffer disabled.
SPI_PULL_WEAK Control of SPI pull-down resistor strength [4:4] 1b0
0- strong pull-down (default)
1 - weak pull-down.
MISO_SR_CTRL MISO Slew Rate control [3:3] 1b1
0 - SR control disabled without static current (fast rise/fall time ~<1ns). (Contact
sales office before enabling)
1 - SR control enabled with static current (default)
DRY_SR_CTRL DRY Slew Rate control [2:2] 1b1
0 - SR control disabled without static current (fast rise/fall time ~<1ns). (Contact
sales office before enabling)
1 - SR control enabled with static current (default)
DRY_HI_SPD DRY High-Speed mode control [1:1] 1b0
0 – 10 MHz mode, SafeSPI2 standard
1 – 25 MHz mode, non-standard high-speed SPI (Contact sales office before
enabling)
MISO_HI_SPD MISO High Speed mode control [0:0] 1b0
0 – 10 MHz mode, SafeSPI2 standard
1 – 25 MHz mode, non-standard high-speed SPI. (Contact sales office before
enabling)
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides a detailed description of the CTRL_USER_IF register bits, including their functions and default values. This fits well under 'specifications' as it specifies the behavior and configuration of the register. The filename captures the essence of the content, making it easily discoverable.
