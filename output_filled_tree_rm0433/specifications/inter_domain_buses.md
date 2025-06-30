# Description of inter-domain bus architecture

**Source**: Page 107, Chunk 831  
**Category**: Description of inter-domain bus architecture  
**Chunk Index**: 831

---

RM0433 Memory and bus architecture
2.1.4 Inter-domain buses
D2-to-D1 AHB
This 32-bit bus connects the D2 domain to the AXI bus matrix in the D1 domain. It allows
bus masters in the D2 domain to access resources (bus slaves) in the D1 domain and
indirectly, via the D1-to-D3 AHB, in the D3 domain.
D1-to-D2 AHB
This 32-bit bus connects the D1 domain to the D2 domain AHB bus matrix. It allows bus
masters in the D1 domain to access resources (bus slaves) in the D2 domain.
D1-to-D3 AHB
This 32-bit bus connects the D1 domain to the D3 domain AHB bus matrix. It allows bus
masters in the D1 domain to access resources (bus slaves) in the D3 domain.
D2-to-D3 AHB
This 32-bit bus connects the D2 domain to the D3 domain AHB bus matrix. It allows bus
masters in the D2 domain to access resources (bus slaves) in the D3 domain.
Cortex®-M7 AXIM bus
The Cortex®-M7 CPU uses the 64-bit AXIM bus to access all memories (excluding ITCM,

---

**AI Reasoning**: The content describes the architecture and function of various inter-domain buses within the STM32 microcontroller, which fits under the broad category of specifications. This organization allows users to easily find detailed technical descriptions related to the hardware's internal bus architecture.
