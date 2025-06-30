# This content describes the features and functional description of general-purpose timers TIM2, TIM3, TIM4, and TIM5.

**Source**: Page 41, Chunk 202  
**Category**: This content describes the features and functional description of general-purpose timers TIM2, TIM3, TIM4, and TIM5.  
**Chunk Index**: 202

---

39.1 TIM2/TIM3/TIM4/TIM5 introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . 1631
39.2 TIM2/TIM3/TIM4/TIM5 main features . . . . . . . . . . . . . . . . . . . . . . . . . . 1631
39.3 TIM2/TIM3/TIM4/TIM5 functional description . . . . . . . . . . . . . . . . . . . . 1633
39.3.1 Time-base unit . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1633
39.3.2 Counter modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1635
39.3.3 Clock selection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1645
39.3.4 Capture/Compare channels . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1649
39.3.5 Input capture mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1650
39.3.6 PWM input mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1651
39.3.7 Forced output mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1652
39.3.8 Output compare mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1653
39.3.9 PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1654
39.3.10 Asymmetric PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1657
39.3.11 Combined PWM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1658
39.3.12 Clearing the OCxREF signal on an external event . . . . . . . . . . . . . . 1659
39.3.13 One-pulse mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1661
39.3.14 Retriggerable one pulse mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1662
39.3.15 Encoder interface mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1663
39.3.16 UIF bit remapping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1665
39.3.17 Timer input XOR function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1665
39.3.18 Timers and external trigger synchronization . . . . . . . . . . . . . . . . . . . 1666
39.3.19 Timer synchronization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1669
39.3.20 DMA burst mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1674
39.3.21 Debug mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1675
39.4 TIM2/TIM3/TIM4/TIM5 registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1676
39.4.1 TIMx control register 1 (TIMx_CR1)(x = 2 to 5) . . . . . . . . . . . . . . . . . 1676
39.4.2 TIMx control register 2 (TIMx_CR2)(x = 2 to 5) . . . . . . . . . . . . . . . . . 1677
39.4.3 TIMx slave mode control register (TIMx_SMCR)(x = 2 to 5) . . . . . . . 1679
39.4.4 TIMx DMA/Interrupt enable register (TIMx_DIER)(x = 2 to 5) . . . . . . 1682
39.4.5 TIMx status register (TIMx_SR)(x = 2 to 5) . . . . . . . . . . . . . . . . . . . . 1683
39.4.6 TIMx event generation register (TIMx_EGR)(x = 2 to 5) . . . . . . . . . . 1684
39.4.7 TIMx capture/compare mode register 1 (TIMx_CCMR1)(x = 2 to 5) . 1686
RM0433 Rev 8 41/3353
70

---

**AI Reasoning**: The content primarily focuses on the features and functional description of specific timers (TIM2, TIM3, TIM4, TIM5) used in the microcontroller. Placing it under 'features' makes it easily discoverable for users looking for detailed information about the capabilities and functionalities of these timers. The filename captures the essence of the content by specifying the timers discussed.
