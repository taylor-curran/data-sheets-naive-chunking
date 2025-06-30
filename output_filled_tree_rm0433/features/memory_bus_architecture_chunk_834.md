# Overview of memory and bus architecture including LTDC, Ethernet MAC, and USBHS peripherals

**Source**: Page 109, Chunk 834  
**Category**: Overview of memory and bus architecture including LTDC, Ethernet MAC, and USBHS peripherals  
**Chunk Index**: 834

---

RM0433 Memory and bus architecture
LCD-TFT controller (LTDC)
The LCD-TFT display controller, LTDC, uses a 64-bit bus, connected to the AXI bus matrix,
through which it can access internal AXI SRAM and Flash memories, and external
memories through the Quad-SPI controller and the FMC.
Ethernet MAC
The Ethernet MAC uses a 32-bit bus, connected to the AHB bus matrix in the D2 domain.
Through the system bus matrices, it can access all internal memories except ITCM and
DTCM, and external memories through the Quad-SPI controller and the FMC.
USBHS1 and USBHS2 peripherals
The USBHS1 and USBHS2 peripherals use 32-bit buses, connected to the AHB bus matrix
in the D2 domain. Through the system bus matrices, they can access all internal memories
except ITCM and DTCM, and external memories through the Quad-SPI controller and the
FMC.
Upon reset, clocks to blocks such as peripherals and some memories are disabled (except
for the SRAM, DTCM, ITCM and Flash memory). To operate a block with no clock upon

---

**AI Reasoning**: The content primarily discusses the memory and bus architecture of the STM32H7 series, focusing on how different controllers and peripherals interact with the memory system. This fits well under 'features' as it describes the functional aspects of the microcontroller's architecture.
