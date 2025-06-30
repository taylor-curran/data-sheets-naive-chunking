# Detailed description of DMA2D features and registers

**Source**: Page 18, Chunk 142  
**Category**: Detailed description of DMA2D features and registers  
**Chunk Index**: 142

---

18.2 DMA2D main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 715
18.3 DMA2D functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 716
18.3.1 General description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 716
18.3.2 DMA2D internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 717
18.3.3 DMA2D control . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 717
18.3.4 DMA2D foreground and background FIFOs . . . . . . . . . . . . . . . . . . . . 718
18.3.5 DMA2D foreground and background PFC . . . . . . . . . . . . . . . . . . . . . . 718
18.3.6 DMA2D foreground and background CLUT interface . . . . . . . . . . . . . 720
18.3.7 DMA2D blender . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 721
18.3.8 DMA2D output PFC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 721
18.3.9 DMA2D output FIFO . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 722
18.3.10 DMA2D output FIFO byte reordering . . . . . . . . . . . . . . . . . . . . . . . . . . 723
18.3.11 DMA2D AXI master port timer . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 724
18.3.12 DMA2D transactions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 724
18.3.13 DMA2D configuration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 725
18.3.14 YCbCr support . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 729
18.3.15 DMA2D transfer control (start, suspend, abort, and completion) . . . . . 729
18.3.16 Watermark . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 729
18.3.17 Error management . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 729
18.3.18 AXI dead time . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 730
18.4 DMA2D interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 730
18.5 DMA2D registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 731
18.5.1 DMA2D control register (DMA2D_CR) . . . . . . . . . . . . . . . . . . . . . . . . 731
18.5.2 DMA2D interrupt status register (DMA2D_ISR) . . . . . . . . . . . . . . . . . 732
18.5.3 DMA2D interrupt flag clear register (DMA2D_IFCR) . . . . . . . . . . . . . . 733
18.5.4 DMA2D foreground memory address register (DMA2D_FGMAR) . . . 734
18.5.5 DMA2D foreground offset register (DMA2D_FGOR) . . . . . . . . . . . . . . 734
18.5.6 DMA2D background memory address register (DMA2D_BGMAR) . . 735
18.5.7 DMA2D background offset register (DMA2D_BGOR) . . . . . . . . . . . . . 735
18.5.8 DMA2D foreground PFC control register (DMA2D_FGPFCCR) . . . . . 736
18.5.9 DMA2D foreground color register (DMA2D_FGCOLR) . . . . . . . . . . . . 737
18.5.10 DMA2D background PFC control register (DMA2D_BGPFCCR) . . . . 738
18.5.11 DMA2D background color register (DMA2D_BGCOLR) . . . . . . . . . . . 739
18.5.12 DMA2D foreground CLUT memory address register
18/3353 RM0433 Rev 8

---

**AI Reasoning**: The content chunk provides a detailed breakdown of the DMA2D features and its associated registers, which are integral to understanding the functionality of this component. Grouping it under 'features' makes it easily accessible for users looking for specific capabilities and configurations of the DMA2D. The filename captures the essence of the content by highlighting both the features and the registers discussed.
