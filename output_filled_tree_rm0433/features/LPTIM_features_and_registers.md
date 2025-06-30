# Low-Power Timer (LPTIM) features and register details

**Source**: Page 47, Chunk 215  
**Category**: Low-Power Timer (LPTIM) features and register details  
**Chunk Index**: 215

---

RM0433 Contents
43.2 LPTIM main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1860
43.3 LPTIM implementation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1861
43.4 LPTIM functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1861
43.4.1 LPTIM block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1861
43.4.2 LPTIM pins and internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1863
43.4.3 LPTIM input and trigger mapping . . . . . . . . . . . . . . . . . . . . . . . . . . . 1863
43.4.4 LPTIM reset and clocks . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1866
43.4.5 Glitch filter . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1866
43.4.6 Prescaler . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1867
43.4.7 Trigger multiplexer . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1868
43.4.8 Operating mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1868
43.4.9 Timeout function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1870
43.4.10 Waveform generation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1870
43.4.11 Register update . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1871
43.4.12 Counter mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1872
43.4.13 Timer enable . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1872
43.4.14 Timer counter reset . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1873
43.4.15 Encoder mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1873
43.4.16 Debug mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1875
43.5 LPTIM low-power modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1875
43.6 LPTIM interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1876
43.7 LPTIM registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1876
43.7.1 LPTIM interrupt and status register (LPTIM_ISR) . . . . . . . . . . . . . . . 1877
43.7.2 LPTIM interrupt clear register (LPTIM_ICR) . . . . . . . . . . . . . . . . . . . 1878
43.7.3 LPTIM interrupt enable register (LPTIM_IER) . . . . . . . . . . . . . . . . . . 1878
43.7.4 LPTIM configuration register (LPTIM_CFGR) . . . . . . . . . . . . . . . . . . 1879
43.7.5 LPTIM control register (LPTIM_CR) . . . . . . . . . . . . . . . . . . . . . . . . . 1882
43.7.6 LPTIM compare register (LPTIM_CMP) . . . . . . . . . . . . . . . . . . . . . . 1884
43.7.7 LPTIM autoreload register (LPTIM_ARR) . . . . . . . . . . . . . . . . . . . . . 1884
43.7.8 LPTIM counter register (LPTIM_CNT) . . . . . . . . . . . . . . . . . . . . . . . . 1885
43.7.9 LPTIM configuration register 2 (LPTIM_CFGR2) . . . . . . . . . . . . . . . 1885
43.7.10 LPTIM3 configuration register 2 (LPTIM3_CFGR2) . . . . . . . . . . . . . 1886
43.7.11 LPTIM register map . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1887
44 System window watchdog (WWDG) . . . . . . . . . . . . . . . . . . . . . . . . . 1888
RM0433 Rev 8 47/3353
70

---

**AI Reasoning**: The content chunk primarily discusses the features, implementation, functional description, low-power modes, interrupts, and registers of the Low-Power Timer (LPTIM) in the STM32 microcontroller. Grouping it under 'features' provides a broad category that encompasses both the functional aspects and the detailed register information, making it easily discoverable for users interested in LPTIM specifics.
