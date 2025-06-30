# Detailed information on FDCAN registers and their configurations

**Source**: Page 61, Chunk 246  
**Category**: Detailed information on FDCAN registers and their configurations  
**Chunk Index**: 246

---

RM0433 Contents
56.4.23 FDCAN trigger memory element . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2521
56.5 FDCAN registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2523
56.5.1 FDCAN core release register (FDCAN_CREL) . . . . . . . . . . . . . . . . . 2523
56.5.2 FDCAN Endian register (FDCAN_ENDN) . . . . . . . . . . . . . . . . . . . . . 2523
56.5.3 FDCAN data bit timing and prescaler register (FDCAN_DBTP) . . . . 2524
56.5.4 FDCAN test register (FDCAN_TEST) . . . . . . . . . . . . . . . . . . . . . . . . 2525
56.5.5 FDCAN RAM watchdog register (FDCAN_RWD) . . . . . . . . . . . . . . . 2525
56.5.6 FDCAN CC control register (FDCAN_CCCR) . . . . . . . . . . . . . . . . . . 2526
56.5.7 FDCAN nominal bit timing and prescaler register (FDCAN_NBTP) . 2528
56.5.8 FDCAN timestamp counter configuration register (FDCAN_TSCC) . 2529
56.5.9 FDCAN timestamp counter value register (FDCAN_TSCV) . . . . . . . 2530
56.5.10 FDCAN timeout counter configuration register (FDCAN_TOCC) . . . 2530
56.5.11 FDCAN timeout counter value register (FDCAN_TOCV) . . . . . . . . . 2531
56.5.12 FDCAN error counter register (FDCAN_ECR) . . . . . . . . . . . . . . . . . 2532
56.5.13 FDCAN protocol status register (FDCAN_PSR) . . . . . . . . . . . . . . . . 2532
56.5.14 FDCAN transmitter delay compensation register (FDCAN_TDCR) . . 2534
56.5.15 FDCAN interrupt register (FDCAN_IR) . . . . . . . . . . . . . . . . . . . . . . . 2535
56.5.16 FDCAN interrupt enable register (FDCAN_IE) . . . . . . . . . . . . . . . . . 2538
56.5.17 FDCAN interrupt line select register (FDCAN_ILS) . . . . . . . . . . . . . . 2540
56.5.18 FDCAN interrupt line enable register (FDCAN_ILE) . . . . . . . . . . . . . 2541
56.5.19 FDCAN global filter configuration register (FDCAN_GFC) . . . . . . . . 2542
56.5.20 FDCAN standard ID filter configuration register (FDCAN_SIDFC) . . 2543
56.5.21 FDCAN extended ID filter configuration register (FDCAN_XIDFC) . . 2543
56.5.22 FDCAN extended ID and mask register (FDCAN_XIDAM) . . . . . . . . 2544
56.5.23 FDCAN high priority message status register (FDCAN_HPMS) . . . . 2545
56.5.24 FDCAN new data 1 register (FDCAN_NDAT1) . . . . . . . . . . . . . . . . . 2545
56.5.25 FDCAN new data 2 register (FDCAN_NDAT2) . . . . . . . . . . . . . . . . . 2546
56.5.26 FDCAN Rx FIFO 0 configuration register (FDCAN_RXF0C) . . . . . . . 2546
56.5.27 FDCAN Rx FIFO 0 status register (FDCAN_RXF0S) . . . . . . . . . . . . 2547
56.5.28 FDCAN Rx FIFO 0 acknowledge register (FDCAN_RXF0A) . . . . . . 2548
56.5.29 FDCAN Rx buffer configuration register (FDCAN_RXBC) . . . . . . . . . 2548
56.5.30 FDCAN Rx FIFO 1 configuration register (FDCAN_RXF1C) . . . . . . . 2549
56.5.31 FDCAN Rx FIFO 1 status register (FDCAN_RXF1S) . . . . . . . . . . . . 2550
56.5.32 FDCAN Rx FIFO 1 acknowledge register (FDCAN_RXF1A) . . . . . . 2551
56.5.33 FDCAN Rx buffer element size configuration register
56.5.34 FDCAN Tx buffer configuration register (FDCAN_TXBC) . . . . . . . . . 2552
RM0433 Rev 8 61/3353

---

**AI Reasoning**: The content chunk primarily focuses on the FDCAN registers, detailing various configuration and status registers. This fits well under 'specifications' as it provides technical details about the FDCAN module. A single file named 'fdcan_registers.md' captures the essence of the content, making it easy to locate within the 'specifications' directory.
