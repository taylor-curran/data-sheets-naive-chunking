# Quad-SPI interface features and functional description

**Source**: Page 22, Chunk 152  
**Category**: Quad-SPI interface features and functional description  
**Chunk Index**: 152

---

23.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 879
23.2 QUADSPI main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 879
23.3 QUADSPI functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 879
23.3.1 QUADSPI block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 879
23.3.2 QUADSPI pins and internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . 880
23.3.3 QUADSPI command sequence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 881
23.3.4 QUADSPI signal interface protocol modes . . . . . . . . . . . . . . . . . . . . . 883
23.3.5 QUADSPI indirect mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 885
23.3.6 QUADSPI automatic status-polling mode . . . . . . . . . . . . . . . . . . . . . . 887
23.3.7 QUADSPI memory-mapped mode . . . . . . . . . . . . . . . . . . . . . . . . . . . 887
23.3.8 QUADSPI free-running clock mode . . . . . . . . . . . . . . . . . . . . . . . . . . . 888
23.3.9 QUADSPI flash memory configuration . . . . . . . . . . . . . . . . . . . . . . . . 888
23.3.10 QUADSPI delayed data sampling . . . . . . . . . . . . . . . . . . . . . . . . . . . . 889
23.3.11 QUADSPI configuration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 889
23.3.12 QUADSPI use . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 889
23.3.13 Sending the instruction only once . . . . . . . . . . . . . . . . . . . . . . . . . . . . 891
23.3.14 QUADSPI error management . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 892
23.3.15 QUADSPI busy bit and abort functionality . . . . . . . . . . . . . . . . . . . . . . 892
23.3.16 NCS behavior . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 892
23.4 QUADSPI interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 894
23.5 QUADSPI registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 895
23.5.1 QUADSPI control register (QUADSPI_CR) . . . . . . . . . . . . . . . . . . . . . 895
23.5.2 QUADSPI device configuration register (QUADSPI_DCR) . . . . . . . . . 897
23.5.3 QUADSPI status register (QUADSPI_SR) . . . . . . . . . . . . . . . . . . . . . 898
23.5.4 QUADSPI flag clear register (QUADSPI_FCR) . . . . . . . . . . . . . . . . . . 899
23.5.5 QUADSPI data length register (QUADSPI_DLR) . . . . . . . . . . . . . . . . 900
23.5.6 QUADSPI communication configuration register (QUADSPI_CCR) . . 900
22/3353 RM0433 Rev 8

---

**AI Reasoning**: The content chunk provides an overview of the Quad-SPI interface, including its main features, functional description, and related registers. It fits well under a 'features' category as it details the capabilities and functionalities of the Quad-SPI interface, which is a key feature of the microcontroller.
