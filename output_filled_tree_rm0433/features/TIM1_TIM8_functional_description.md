# Detailed description of TIM1/TIM8 features and functionalities

**Source**: Page 39, Chunk 199  
**Category**: Detailed description of TIM1/TIM8 features and functionalities  
**Chunk Index**: 199

---

RM0433 Contents
38.2 TIM1/TIM8 main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1527
38.3 TIM1/TIM8 functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1529
38.3.1 Time-base unit . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1529
38.3.2 Counter modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1531
38.3.3 Repetition counter . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1542
38.3.4 External trigger input . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1544
38.3.5 Clock selection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1545
38.3.6 Capture/compare channels . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1549
38.3.7 Input capture mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1551
38.3.8 PWM input mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1552
38.3.9 Forced output mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1553
38.3.10 Output compare mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1554
38.3.11 PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1555
38.3.12 Asymmetric PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1558
38.3.13 Combined PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1559
38.3.14 Combined 3-phase PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1560
38.3.15 Complementary outputs and dead-time insertion . . . . . . . . . . . . . . . 1561
38.3.16 Using the break function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1563
38.3.17 Bidirectional break inputs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1569
38.3.18 Clearing the OCxREF signal on an external event . . . . . . . . . . . . . . 1569
38.3.19 6-step PWM generation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1571
38.3.20 One-pulse mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1572
38.3.21 Retriggerable one pulse mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1573
38.3.22 Encoder interface mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1574
38.3.23 UIF bit remapping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1576
38.3.24 Timer input XOR function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1577
38.3.25 Interfacing with Hall sensors . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1577
38.3.26 Timer synchronization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1580
38.3.27 ADC synchronization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1584
38.3.28 DMA burst mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1584
38.3.29 Debug mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1585
38.4 TIM1/TIM8 registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1586
38.4.1 TIMx control register 1 (TIMx_CR1)(x = 1, 8) . . . . . . . . . . . . . . . . . . 1586
38.4.2 TIMx control register 2 (TIMx_CR2)(x = 1, 8) . . . . . . . . . . . . . . . . . . 1587
38.4.3 TIMx slave mode control register
(TIMx_SMCR)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1590
RM0433 Rev 8 39/3353
70

---

**AI Reasoning**: The content chunk provides an in-depth functional description of TIM1/TIM8, including various modes and configurations. It fits well under 'features' as it elaborates on the capabilities and functionalities of these timers. The filename captures the essence of the content, making it easily discoverable.
