# Description of bus master peripherals and their connections

**Source**: Page 108, Chunk 833  
**Category**: Description of bus master peripherals and their connections  
**Chunk Index**: 833

---

Memory and bus architecture RM0433
2.1.6 Bus master peripherals
SDMMC1
The SDMMC1 uses a 32-bit bus, connected to the AXI bus matrix, through which it can
access internal AXI SRAM and Flash memories, and external memories through the Quad-
SPI controller and the FMC.
SDMMC2
The SDMMC2 uses a 32-bit bus, connected to the AHB bus matrix in D2 domain. Through
the system bus matrices, it can access the internal AXI SRAM, SRAM1, SRAM2, SRAM3
and Flash memories, and external memories through the Quad-SPI controller and the FMC.
MDMA controller
The MDMA controller has two bus masters: an AXI 64-bit bus, connected to the AXI bus
matrix and an AHB 32-bit bus connected to the Cortex-M7 AHBS slave bus.
The MDMA is optimized for DMA data transfers between memories since it supports linked
list transfers that allow performing a chained list of transfers without the need for CPU
intervention. Through the system bus matrices and the Cortex-M7 AHBS slave bus, the
MDMA can access all internal and external memories through the Quad-SPI controller and
the FMC.
DMA1 and DMA2 controllers
The DMA1 and DMA2 controllers have two 32-bit buses - memory bus and peripheral bus,
connected to the AHB bus matrix in D2 domain.
The memory bus allows DMA data transfers between memories. Through the system bus
matrices, the memory bus can access all internal memories except ITCM and DTCM, and
external memories through the Quad-SPI controller and the FMC.
The peripheral bus allows DMA data transfers between two peripherals, between two
memories or between a peripheral and a memory. Through the system bus matrices, the
peripheral bus can access all internal memories except ITCM and DTCM, external
memories through the Quad-SPI controller and the FMC, and all AHB and APB peripherals.
A direct access to APB1 and APB2 is available, without passing through AHB1. Direct path
to APB1 and APB2 bridges allows reducing the bandwidth usage on AHB1 bus by improving
data treatment efficiency for APB and AHB peripherals.
BDMA controller
The BDMA controller uses a 32-bit bus, connected to the AHB bus matrix in D3 domain, for
DMA data transfers between two peripherals, between two memories or between a
peripheral and a memory. BDMA transfers are limited to the D3 domain resources. It can
access the internal SRAM4, backup RAM, and AHB4 and APB4 peripherals through the
AHB bus matrix in the D3 domain.
Chrom-Art Accelerator (DMA2D)
The DMA2D graphics accelerator uses a 64-bit bus, connected to the AXI bus matrix.
Through the system bus matrices, internal AXI SRAM, SRAM1, SRAM2, SRAM3 and Flash
memories, and external memories through the Quad-SPI controller and the FMC.
108/3353 RM0433 Rev 8

---

**AI Reasoning**: The content describes various bus master peripherals and their connectivity within the STM32 microcontroller architecture. It fits under 'specifications' as it details the technical configuration and capabilities of these components. A shallow directory structure with a focus on specifications ensures easy access and understanding of the hardware's architecture.
