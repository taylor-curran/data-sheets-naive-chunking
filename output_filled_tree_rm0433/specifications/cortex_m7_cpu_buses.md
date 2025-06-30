# Description of the CPU buses used by the Cortex-M7

**Source**: Page 107, Chunk 832  
**Category**: Description of the CPU buses used by the Cortex-M7  
**Chunk Index**: 832

---

2.1.5 CPU buses
Cortex®-M7 AXIM bus
The Cortex®-M7 CPU uses the 64-bit AXIM bus to access all memories (excluding ITCM,
and DTCM) and AHB3, AHB4, APB3 and APB4 peripherals (excluding AHB1, APB1 and
APB2 peripherals).
The AXIM bus connects the CPU to the AXI bus matrix in the D1 domain.
Cortex®-M7 ITCM bus
The Cortex®-M7 CPU uses the 64-bit ITCM bus for fetching instructions from and accessing
data in the ITCM.
Cortex®-M7 DTCM bus
The Cortex®-M7 CPU uses the 2x32-bit DTCM bus for accessing data in the DTCM. The
2x32-bit DTCM bus allows load/load and load/store instruction pairs to be dual-issued on
the DTCM memory. It can also fetch instructions.
Cortex®-M7 AHBS bus
The Cortex®-M7 CPU uses the 32-bit AHBS slave bus to allow the MDMA controller to
access the ITCM and the DTCM.
Cortex®-M7 AHBP bus
The Cortex®-M7 CPU uses the 32-bit AHBP bus for accessing AHB1, AHB2, APB1 and
APB2 peripherals via the AHB bus matrix in the D2 domain.
RM0433 Rev 8 107/3353
128

---

**AI Reasoning**: The content describes various CPU buses used by the Cortex-M7, which is a technical specification of the microcontroller's architecture. Placing it under 'specifications' makes it easy to find for those looking for detailed technical information about the CPU's bus architecture.
