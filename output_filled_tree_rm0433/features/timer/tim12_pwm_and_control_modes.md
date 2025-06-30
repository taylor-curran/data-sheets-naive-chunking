# Detailed description of TIM12 PWM and control modes

**Source**: Page 43, Chunk 206  
**Category**: Detailed description of TIM12 PWM and control modes  
**Chunk Index**: 206

---

RM0433 Contents
40.3.6 PWM input mode (only for TIM12) . . . . . . . . . . . . . . . . . . . . . . . . . . . 1721
40.3.7 Forced output mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1722
40.3.8 Output compare mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1723
40.3.9 PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1724
40.3.10 Combined PWM mode (TIM12 only) . . . . . . . . . . . . . . . . . . . . . . . . . 1725
40.3.11 One-pulse mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1726
40.3.12 Retriggerable one pulse mode (TIM12 only) . . . . . . . . . . . . . . . . . . . 1728
40.3.13 UIF bit remapping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1728
40.3.14 Timer input XOR function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1729
40.3.15 TIM12 external trigger synchronization . . . . . . . . . . . . . . . . . . . . . . . 1729
40.3.16 Slave mode – combined reset + trigger mode . . . . . . . . . . . . . . . . . . 1732
40.3.17 Timer synchronization (TIM12) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1733
40.3.18 Using timer output as trigger for other timers (TIM13/TIM14) . . . . . . 1733
40.3.19 Debug mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1733
40.4 TIM12 registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1733
40.4.1 TIM12 control register 1 (TIM12_CR1) . . . . . . . . . . . . . . . . . . . . . . . 1733
40.4.2 TIM12 control register 2 (TIM12_CR2) . . . . . . . . . . . . . . . . . . . . . . . 1734
40.4.3 TIM12 slave mode control register (TIM12_SMCR) . . . . . . . . . . . . . 1735
40.4.4 TIM12 Interrupt enable register (TIM12_DIER) . . . . . . . . . . . . . . . . . 1737
40.4.5 TIM12 status register (TIM12_SR) . . . . . . . . . . . . . . . . . . . . . . . . . . 1737
40.4.6 TIM12 event generation register (TIM12_EGR) . . . . . . . . . . . . . . . . 1738
40.4.7 TIM12 capture/compare mode register 1 (TIM12_CCMR1) . . . . . . . 1739
40.4.8 TIM12 capture/compare mode register 1 [alternate]
40.4.9 TIM12 capture/compare enable register (TIM12_CCER) . . . . . . . . . 1743
40.4.10 TIM12 counter (TIM12_CNT) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1744

---

**AI Reasoning**: This content chunk focuses on the various modes and registers associated with the TIM12 timer, including PWM input, output compare, and control registers. Grouping it under 'features/timer' makes it easy to locate for users interested in timer functionalities and configurations.
