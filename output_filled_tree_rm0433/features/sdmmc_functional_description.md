# Detailed description of SDMMC functionality and operation

**Source**: Page 59, Chunk 242  
**Category**: Detailed description of SDMMC functionality and operation  
**Chunk Index**: 242

---

RM0433 Contents
55.3 SDMMC bus topology . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2379
55.4 SDMMC operation modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2381
55.5 SDMMC functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2382
55.5.1 SDMMC block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2382
55.5.2 SDMMC pins and internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . 2382
55.5.3 General description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2383
55.5.4 SDMMC adapter . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2385
55.5.5 SDMMC AHB slave interface . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2407
55.5.6 SDMMC AHB master interface . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2407
55.5.7 MDMA request generation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2409
55.5.8 AHB and SDMMC_CK clock relation . . . . . . . . . . . . . . . . . . . . . . . . . 2410
55.6 Card functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .2411
55.6.1 SD I/O mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2411
55.6.2 CMD12 send timing . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2419
55.6.3 Sleep (CMD5) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2422
55.6.4 Interrupt mode (Wait-IRQ) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2423
55.6.5 Boot operation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2424
55.6.6 Response R1b handling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2427
55.6.7 Reset and card cycle power . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2428
55.7 Hardware flow control . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2429
55.8 Ultra-high-speed phase I (UHS-I) voltage switch . . . . . . . . . . . . . . . . . 2430
55.9 SDMMC interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2433
55.10 SDMMC registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2435
55.10.1 SDMMC power control register (SDMMC_POWER) . . . . . . . . . . . . . 2435
55.10.2 SDMMC clock control register (SDMMC_CLKCR) . . . . . . . . . . . . . . 2436
55.10.3 SDMMC argument register (SDMMC_ARGR) . . . . . . . . . . . . . . . . . . 2438
55.10.4 SDMMC command register (SDMMC_CMDR) . . . . . . . . . . . . . . . . . 2438
55.10.5 SDMMC command response register (SDMMC_RESPCMDR) . . . . 2440
55.10.6 SDMMC response x register (SDMMC_RESPxR) . . . . . . . . . . . . . . 2441
55.10.7 SDMMC data timer register (SDMMC_DTIMER) . . . . . . . . . . . . . . . 2441
55.10.8 SDMMC data length register (SDMMC_DLENR) . . . . . . . . . . . . . . . 2442
55.10.9 SDMMC data control register (SDMMC_DCTRL) . . . . . . . . . . . . . . . 2443
55.10.10 SDMMC data counter register (SDMMC_DCNTR) . . . . . . . . . . . . . . 2444
55.10.11 SDMMC status register (SDMMC_STAR) . . . . . . . . . . . . . . . . . . . . . 2445
55.10.12 SDMMC interrupt clear register (SDMMC_ICR) . . . . . . . . . . . . . . . . 2448
55.10.13 SDMMC mask register (SDMMC_MASKR) . . . . . . . . . . . . . . . . . . . . 2450
RM0433 Rev 8 59/3353
70

---

**AI Reasoning**: The content chunk provides a comprehensive overview of the SDMMC (Secure Digital Memory Card Controller) including its bus topology, operation modes, functional description, and registers. This fits well under 'features' as it describes the capabilities and functionalities of the SDMMC component in the microcontroller. The filename captures the essence of the content, focusing on the functional description aspect.
