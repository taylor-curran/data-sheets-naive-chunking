# Detailed description of OTG_HS features and registers

**Source**: Page 64, Chunk 255  
**Category**: Detailed description of OTG_HS features and registers  
**Chunk Index**: 255

---

Contents RM0433
57.8.1 Host SOFs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2607
57.8.2 Peripheral SOFs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2607
57.9 OTG_HS low-power modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2608
57.10 OTG_HS Dynamic update of the OTG_HFIR register . . . . . . . . . . . . . 2609
57.11 OTG_HS data FIFOs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2609
57.11.1 Peripheral FIFO architecture . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2610
57.11.2 Host FIFO architecture . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2611
57.11.3 FIFO RAM allocation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2612
57.12 OTG_HS interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2614
57.13 OTG_HS control and status registers . . . . . . . . . . . . . . . . . . . . . . . . . 2616
57.13.1 CSR memory map . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2616
57.14 OTG_HS registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2621
57.14.1 OTG control and status register (OTG_GOTGCTL) . . . . . . . . . . . . . 2621
57.14.2 OTG interrupt register (OTG_GOTGINT) . . . . . . . . . . . . . . . . . . . . . 2624
57.14.3 OTG AHB configuration register (OTG_GAHBCFG) . . . . . . . . . . . . . 2626
57.14.4 OTG USB configuration register (OTG_GUSBCFG) . . . . . . . . . . . . . 2627
57.14.5 OTG reset register (OTG_GRSTCTL) . . . . . . . . . . . . . . . . . . . . . . . . 2630
57.14.6 OTG core interrupt register (OTG_GINTSTS) . . . . . . . . . . . . . . . . . . 2633
57.14.7 OTG interrupt mask register (OTG_GINTMSK) . . . . . . . . . . . . . . . . . 2637
57.14.8 OTG receive status debug read register (OTG_GRXSTSR) . . . . . . . 2641
57.14.9 OTG receive status debug read [alternate] (OTG_GRXSTSR) . . . . . 2642
57.14.10 OTG status read and pop registers (OTG_GRXSTSP) . . . . . . . . . . . 2643
57.14.11 OTG status read and pop registers [alternate] (OTG_GRXSTSP) . . 2644
57.14.12 OTG receive FIFO size register (OTG_GRXFSIZ) . . . . . . . . . . . . . . 2645
57.14.13 OTG host non-periodic transmit FIFO size register
(OTG_HNPTXFSIZ)/Endpoint 0 Transmit FIFO size
57.14.14 OTG non-periodic transmit FIFO/queue status register

---

**AI Reasoning**: The content chunk primarily discusses various features and registers related to the OTG_HS (On-The-Go High-Speed) functionality. This includes low-power modes, dynamic updates, FIFO architectures, interrupts, and control/status registers. Grouping these under 'features' provides a broad yet relevant category, and the filename captures the essence of the content, making it easily discoverable.
