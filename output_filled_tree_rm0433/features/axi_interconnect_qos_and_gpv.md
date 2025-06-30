# Description of AXI interconnect QoS and Global Programmer View

**Source**: Page 111, Chunk 846  
**Category**: Description of AXI interconnect QoS and Global Programmer View  
**Chunk Index**: 846

---

TARG 6 QUADSPI AXI4 64 2/1/3
TARG 7 AXI SRAM AXI3 64 2/2/2
1. Conversion to AHB protocol is done via an AXI/AHB bridge sitting between AXI interconnect and the
connected slave.
Quality of service (QoS)
The AXI switch matrix uses a priority-based arbitration when two ASIB simultaneously
attempt to access the same AMIB. Each ASIB has programmable read channel and write
channel priorities, known as QoS, from 0 to 15, such that the higher the value, the higher the
priority. The read channel QoS value is programmed in the AXI interconnect - INI x read
QoS register (AXI_INIx_READ_QOS), and the write channel in the AXI interconnect - INI x
write QoS register (AXI_INIx_WRITE_QOS). The default QoS value for all channels is 0
(lowest priority).
If two coincident transactions arrive at the same AMIB, the higher priority transaction passes
before the lower priority. If the two transactions have the same QoS value, then a least-
recently-used (LRU) priority scheme is adopted.
The QoS values should be programmed according to the latency requirements for the
application. Setting a higher priority for an ASIB ensures a lower latency for transactions
initiated by the associated bus master. This can be useful for real-time-constrained tasks,
such as graphics processing (LTDC, DMA2D). Assigning a high priority to masters that can
make many and frequent accesses to the same slave (such as the Cortex-M7 CPU) can
block access to that slave by other lower-priority masters.
Global programmer view (GPV)
The GPV contains configuration registers for the AXI interconnect (see Section 2.2.4).
These registers are only accessible by the Cortex-M7 CPU.
RM0433 Rev 8 111/3353
128

---

**AI Reasoning**: The content primarily discusses the Quality of Service (QoS) mechanism and the Global Programmer View (GPV) related to the AXI interconnect. These are features of the AXI interconnect system, making 'features' a suitable category. The filename captures the essence of the content by mentioning both QoS and GPV.
