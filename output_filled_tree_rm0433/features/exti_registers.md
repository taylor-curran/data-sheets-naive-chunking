# EXTI registers and configurations

**Source**: Page 20, Chunk 147  
**Category**: EXTI registers and configurations  
**Chunk Index**: 147

---

Contents RM0433
20.5.5 EXTI software interrupt/event trigger procedure . . . . . . . . . . . . . . . . . 771
20.6 EXTI registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 772
20.6.1 EXTI rising trigger selection register (EXTI_RTSR1) . . . . . . . . . . . . . . 772
20.6.2 EXTI falling trigger selection register (EXTI_FTSR1) . . . . . . . . . . . . . 772
20.6.3 EXTI software interrupt event register (EXTI_SWIER1) . . . . . . . . . . . 773
20.6.4 EXTI D3 pending mask register (EXTI_D3PMR1) . . . . . . . . . . . . . . . . 773
20.6.5 EXTI D3 pending clear selection register low (EXTI_D3PCR1L) . . . . 774
20.6.6 EXTI D3 pending clear selection register high (EXTI_D3PCR1H) . . . 774
20.6.7 EXTI rising trigger selection register (EXTI_RTSR2) . . . . . . . . . . . . . . 775
20.6.8 EXTI falling trigger selection register (EXTI_FTSR2) . . . . . . . . . . . . . 776
20.6.9 EXTI software interrupt event register (EXTI_SWIER2) . . . . . . . . . . . 776
20.6.10 EXTI D3 pending mask register (EXTI_D3PMR2) . . . . . . . . . . . . . . . . 777
20.6.11 EXTI D3 pending clear selection register low (EXTI_D3PCR2L) . . . . 778
20.6.12 EXTI D3 pending clear selection register high (EXTI_D3PCR2H) . . . 778
20.6.13 EXTI rising trigger selection register (EXTI_RTSR3) . . . . . . . . . . . . . . 779
20.6.14 EXTI falling trigger selection register (EXTI_FTSR3) . . . . . . . . . . . . . 779
20.6.15 EXTI software interrupt event register (EXTI_SWIER3) . . . . . . . . . . . 780
20.6.16 EXTI D3 pending mask register (EXTI_D3PMR3) . . . . . . . . . . . . . . . . 780
20.6.17 EXTI D3 pending clear selection register low (EXTI_D3PCR3L) . . . . 781
20.6.18 EXTI D3 pending clear selection register high (EXTI_D3PCR3H) . . . 781
20.6.19 EXTI interrupt mask register (EXTI_CPUIMR1) . . . . . . . . . . . . . . . . . 782
20.6.20 EXTI event mask register (EXTI_CPUEMR1) . . . . . . . . . . . . . . . . . . . 782
20.6.21 EXTI pending register (EXTI_CPUPR1) . . . . . . . . . . . . . . . . . . . . . . . 783
20.6.22 EXTI interrupt mask register (EXTI_CPUIMR2) . . . . . . . . . . . . . . . . . 783
20.6.23 EXTI event mask register (EXTI_CPUEMR2) . . . . . . . . . . . . . . . . . . . 784
20.6.24 EXTI pending register (EXTI_CPUPR2) . . . . . . . . . . . . . . . . . . . . . . . 784
20.6.25 EXTI interrupt mask register (EXTI_CPUIMR3) . . . . . . . . . . . . . . . . . 785
20.6.26 EXTI event mask register (EXTI_CPUEMR3) . . . . . . . . . . . . . . . . . . . 786
20.6.27 EXTI pending register (EXTI_CPUPR3) . . . . . . . . . . . . . . . . . . . . . . . 786
20.6.28 EXTI register map . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 787
21 Cyclic redundancy check calculation unit (CRC) . . . . . . . . . . . . . . . . 790

---

**AI Reasoning**: The content primarily discusses various EXTI (External Interrupt/Event Controller) registers and their configurations, which are features of the microcontroller. Grouping this under 'features' makes it easily discoverable for users looking for information on EXTI functionalities.
