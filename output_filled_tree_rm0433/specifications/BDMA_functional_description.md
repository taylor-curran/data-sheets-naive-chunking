# Detailed description of BDMA implementation and functionality

**Source**: Page 16, Chunk 134  
**Category**: Detailed description of BDMA implementation and functionality  
**Chunk Index**: 134

---

16.3.1 BDMA . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 670
16.3.2 BDMA request mapping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 670
16.4 BDMA functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 670
16.4.1 BDMA block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 670
16.4.2 BDMA pins and internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 671
16.4.3 BDMA transfers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 671
16.4.4 BDMA arbitration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 672
16.4.5 BDMA channels . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 672
16.4.6 BDMA data width, alignment and endianness . . . . . . . . . . . . . . . . . . . 677
16.4.7 BDMA error management . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 678
16.5 BDMA interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 679
16.6 BDMA registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 679
16.6.1 BDMA interrupt status register (BDMA_ISR) . . . . . . . . . . . . . . . . . . . . 679
16.6.2 BDMA interrupt flag clear register (BDMA_IFCR) . . . . . . . . . . . . . . . . 682
16.6.3 BDMA channel x configuration register (BDMA_CCRx) . . . . . . . . . . . 683
16.6.4 BDMA channel x number of data to transfer register
(BDMA_CNDTRx) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 687
16.6.5 BDMA channel x peripheral address register (BDMA_CPARx) . . . . . . 687
16.6.6 BDMA channel x memory 0 address register (BDMA_CM0ARx) . . . . 688
16.6.7 BDMA channel x memory 1 address register (BDMA_CM1ARx) . . . . 689
16.6.8 BDMA register map . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 689
16/3353 RM0433 Rev 8

---

**AI Reasoning**: The content chunk provides a detailed breakdown of the BDMA (Basic DMA) implementation, including its functional description, request mapping, block diagram, pins, transfers, arbitration, channels, data handling, error management, interrupts, and registers. This fits well under 'specifications' as it describes the technical details and functionality of the BDMA component in the STM32 microcontroller.
