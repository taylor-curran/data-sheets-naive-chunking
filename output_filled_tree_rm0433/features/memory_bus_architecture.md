# Description of bus matrices and memory architecture in STM32H7 series

**Source**: Page 106, Chunk 828  
**Category**: Description of bus matrices and memory architecture in STM32H7 series  
**Chunk Index**: 828

---

Memory and bus architecture RM0433
2.1.1 Bus matrices
AXI bus matrix in D1 domain
The D1 domain multi AXI bus matrix ensures and arbitrates concurrent accesses from
multiple masters to multiple slaves. This allows efficient simultaneous operation of high-
speed peripherals.
The arbitration uses a round-robin algorithm with QoS capability.
Refer to Section 2.2: AXI interconnect matrix (AXIM) for more information on AXI
interconnect.
AHB bus matrices in D2 and D3 domains
The AHB bus matrices in D2 and D3 domains ensure and arbitrate concurrent accesses
from multiple masters to multiple slaves. This allows efficient simultaneous operation of
high-speed peripherals.
The arbitration uses a round-robin algorithm.
The DTCM and ITCM (data and instruction tightly coupled RAMs) are connected through
dedicated TCM buses directly to the Cortex-M7 core. The MDMA controller can access the

---

**AI Reasoning**: The content discusses the architecture of bus matrices and memory, which are features of the STM32H7 series microcontrollers. Placing it under 'features' makes it easily discoverable for those interested in the technical capabilities and design of the microcontroller.
