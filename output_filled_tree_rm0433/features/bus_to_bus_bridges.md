# Description of bus-to-bus bridges in the system

**Source**: Page 106, Chunk 830  
**Category**: Description of bus-to-bus bridges in the system  
**Chunk Index**: 830

---

2.1.3 Bus-to-bus bridges
To allow peripherals with different types of buses to communicate together, there is a
number of bus-to-bus bridges in the system.
The AHB/APB bridges in D1 and D3 domains allow connecting peripherals on APB3 and
APB4 to AHB3 and AHB4, respectively. The AHB/APB bridges in D2 domain allow
peripherals on APB1 and APB2 to connect to AHB1. These AHB/APB bridges provide full
synchronous interfacing, which allows the APB peripherals to operate with clocks
independent of AHB that they connect to.
The AHB/APB bridges also allow APB1 and APB2 peripherals to connect to DMA1 and
DMA2 peripheral buses, respectively, without transiting through AHB1.
The AHB/APB bridges convert 8-bit / 16-bit APB data to 32-bit AHB data, by replicating it to
the three upper bytes / the upper half-word of the 32-bit word.
The AXI bus matrix incorporates AHB/AXI bus bridge functionality on its slave bus
interfaces. The AXI/AHB bus bridges on its master interfaces marked as 32-bit in Figure 1
are outside the matrix.
The Cortex-M7 CPU provides AHB/TCM-bus (ITCM and DTCM buses) translation from its
AHBS slave AHB, allowing the MDMA controller to access the ITCM and DTCM.
106/3353 RM0433 Rev 8

---

**AI Reasoning**: The content discusses the functionality and purpose of bus-to-bus bridges within the system, which is a feature of the microcontroller architecture. Placing it under 'features' makes it easily discoverable for those looking to understand the capabilities and design of the system. The filename succinctly captures the essence of the content.
