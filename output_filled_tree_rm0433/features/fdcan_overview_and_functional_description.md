# Overview and functional description of FDCAN features and implementation

**Source**: Page 60, Chunk 245  
**Category**: Overview and functional description of FDCAN features and implementation  
**Chunk Index**: 245

---

56.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2459
56.2 FDCAN main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2462
56.3 FDCAN implementation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2462
56.4 FDCAN functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2463
56.4.1 Operating modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2464
56.4.2 Message RAM . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2473
56.4.3 FIFO acknowledge handling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2484
56.4.4 Bit timing . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2485
56.4.5 Clock calibration on CAN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2486
56.4.6 Application . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2490
56.4.7 TTCAN operations (FDCAN1 only) . . . . . . . . . . . . . . . . . . . . . . . . . . 2491
56.4.8 TTCAN configuration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2492
56.4.9 Message scheduling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2494
56.4.10 TTCAN gap control . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2501
56.4.11 Stop watch . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2502
56.4.12 Local time, cycle time, global time,
and external clock synchronization . . . . . . . . . . . . . . . . . . . . . . . . . . 2502
56.4.13 TTCAN error level . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2505
56.4.14 TTCAN message handling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2506
56.4.15 TTCAN interrupt and error handling . . . . . . . . . . . . . . . . . . . . . . . . . 2509
56.4.16 Level 0 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2510
56.4.17 Synchronization to external time schedule . . . . . . . . . . . . . . . . . . . . 2512
56.4.18 FDCAN Rx buffer and FIFO element . . . . . . . . . . . . . . . . . . . . . . . . . 2513
56.4.19 FDCAN Tx buffer element . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2515
56.4.20 FDCAN Tx event FIFO element . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2517
56.4.21 FDCAN standard message ID filter element . . . . . . . . . . . . . . . . . . . 2518
56.4.22 FDCAN extended message ID filter element . . . . . . . . . . . . . . . . . . . 2520
60/3353 RM0433 Rev 8

---

**AI Reasoning**: The content chunk provides a detailed overview of the FDCAN (Flexible Data-rate Controller Area Network) including its main features, implementation, and functional description. It fits well under 'features' as it describes the capabilities and functionalities of the FDCAN module. The filename captures the essence of the content by highlighting both the overview and the functional aspects.
