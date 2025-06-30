# Description of the AXI interconnect matrix and its components

**Source**: Page 109, Chunk 836  
**Category**: Description of the AXI interconnect matrix and its components  
**Chunk Index**: 836

---

2.2 AXI interconnect matrix (AXIM)
2.2.1 AXI introduction
The AXI (advanced extensible interface) interconnect is based on the Arm® CoreLink™
NIC-400 Network Interconnect. The interconnect has six initiator ports, or ASIBs (AMBA
slave interface blocks), and seven target ports, or AMIBs (AMBA master interface blocks).
The ASIBs are connected to the AMIBs via an AXI switch matrix.
Each ASIB is a slave on an AXI bus or AHB (advanced high-performance bus). Similarly,
each AMIB is a master on an AXI or AHB bus. Where an ASIB or AMIB is connected to an
AHB, it converts between the AHB and the AXI protocol.
The AXI interconnect includes a GPV (global programmer view) which contains registers for
configuring certain parameters, such as the QoS (quality of service) level at each ASIB.
Any accesses to unallocated address space are handled by the default slave, which
generates the return signals. This ensures that such transactions complete and do not block
the issuing master and ASIB.
• 64-bit AXI bus switch matrix with six ASIBs and seven AMIBs, in D1 domain
• AHB/AXI bridge function built into the ASIBs

---

**AI Reasoning**: The content describes the AXI interconnect matrix, its components, and functionality, which fits well under 'features' as it highlights a specific capability of the microcontroller. The filename captures the essence of the content, making it easily discoverable.
