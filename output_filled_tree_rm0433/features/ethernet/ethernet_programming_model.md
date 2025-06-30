# Ethernet programming model and guidelines

**Source**: Page 68, Chunk 277  
**Category**: Ethernet programming model and guidelines  
**Chunk Index**: 277

---

Contents RM0433
58.8.2 MTL interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2876
58.8.3 MAC Interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2877
58.9 Ethernet programming model . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2878
58.9.1 DMA initialization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2878
58.9.2 MTL initialization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2879
58.9.3 MAC initialization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2879
58.9.4 Performing normal receive and transmit operation . . . . . . . . . . . . . . 2880
58.9.5 Stopping and starting transmission . . . . . . . . . . . . . . . . . . . . . . . . . . 2881
58.9.6 Programming guidelines for switching to new descriptor list
in RxDMA . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2881
58.9.7 Programming guidelines for switching the AHB clock frequency . . . . 2881
58.9.8 Programming guidelines for MII link state transitions . . . . . . . . . . . . 2882
58.9.9 Programming guidelines for IEEE 1588 timestamping . . . . . . . . . . . 2883
58.9.10 Programming guidelines for PTP offload feature . . . . . . . . . . . . . . . . 2884
58.9.11 Programming guidelines for Energy Efficient Ethernet (EEE) . . . . . . 2888
58.9.12 Programming guidelines for flexible pulse-per-second (PPS) output 2890
58.9.13 Programming guidelines for TSO . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2892
58.9.14 Programming guidelines to perform VLAN filtering on the receive . . 2893
58.10 Descriptors . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2893
58.10.2 Descriptor structure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2894
58.10.3 Transmit descriptor . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2896

---

**AI Reasoning**: The content chunk focuses on the Ethernet programming model, including initialization, operation, and programming guidelines for various Ethernet features. Grouping it under 'features/ethernet' makes it easily discoverable for those looking for Ethernet-related functionalities.
