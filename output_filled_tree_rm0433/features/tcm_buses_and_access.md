# Description of TCM buses and their connection to Cortex-M7

**Source**: Page 106, Chunk 829  
**Category**: Description of TCM buses and their connection to Cortex-M7  
**Chunk Index**: 829

---

2.1.2 TCM buses
The DTCM and ITCM (data and instruction tightly coupled RAMs) are connected through
dedicated TCM buses directly to the Cortex-M7 core. The MDMA controller can access the
DTCM and ITCM through AHBS, a specific CPU slave AHB. The ITCM is accessed by
Cortex-M7 at CPU clock speed, with zero wait states.
To allow peripherals with different types of buses to communicate together, there is a
number of bus-to-bus bridges in the system.

---

**AI Reasoning**: The content discusses the TCM buses and their integration with the Cortex-M7 core, which is a feature of the microcontroller architecture. Placing it under 'features' allows users to find information about the architectural components and their functionalities easily.
