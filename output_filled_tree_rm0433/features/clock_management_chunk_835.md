# Clock management and enabling for functional blocks

**Source**: Page 109, Chunk 835  
**Category**: Clock management and enabling for functional blocks  
**Chunk Index**: 835

---

2.1.7 Clocks to functional blocks
Upon reset, clocks to blocks such as peripherals and some memories are disabled (except
for the SRAM, DTCM, ITCM and Flash memory). To operate a block with no clock upon
reset, the software must first enable its clock through RCC_AHBxENR or RCC_APBxENR
register, respectively.

---

**AI Reasoning**: The content discusses how clocks are managed and enabled for various functional blocks in the microcontroller, which is a feature of the device. The 'features' directory is appropriate for this type of content, and the filename 'clock_management.md' succinctly captures the essence of the topic.
