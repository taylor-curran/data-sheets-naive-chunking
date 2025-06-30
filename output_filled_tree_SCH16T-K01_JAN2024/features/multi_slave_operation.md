# Description of multi-slave operation in SCH16T SPI

**Source**: Page 30, Chunk 94  
**Category**: Description of multi-slave operation in SCH16T SPI  
**Chunk Index**: 94

---

6.3 Multi-slave operation
SCH16T SPI supports several slave devices on single bus by using either multiple chip select lines, one
for each slave, or with one common chip select (CS) and using TA9 and TA8 pins to enable logical
addressing.
Pin 3 (TA9) and pin 4 (TA8) correspond to the bits TA9:9 and TA8:8 included in the SPI MOSI frame.
Issuing a pull-up signal to either pin means that the components TA bit has been flipped as ‘1’ in
component logic level. All options for addressing four slaves are shown in figure below.
Example: Compose MOSI frame targeted to component #3

---

**AI Reasoning**: The content discusses the multi-slave operation feature of the SCH16T SPI, detailing how multiple slave devices can be managed on a single bus. This fits well under the 'features' category as it describes a specific capability of the hardware. The filename 'multi_slave_operation.md' succinctly captures the essence of the content, making it easily discoverable.
