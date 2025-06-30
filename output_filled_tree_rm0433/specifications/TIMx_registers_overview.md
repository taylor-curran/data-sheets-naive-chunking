# Detailed description of TIMx registers for STM32H7 series

**Source**: Page 40, Chunk 200  
**Category**: Detailed description of TIMx registers for STM32H7 series  
**Chunk Index**: 200

---

Contents RM0433
38.4.4 TIMx DMA/interrupt enable register
(TIMx_DIER)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1592
38.4.5 TIMx status register (TIMx_SR)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . 1594
38.4.6 TIMx event generation register (TIMx_EGR)(x = 1, 8) . . . . . . . . . . . . 1596
38.4.7 TIMx capture/compare mode register 1(TIMx_CCMR1)(x = 1, 8) . . . 1597
38.4.8 TIMx capture/compare mode register 1 [alternate]
(TIMx_CCMR1)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1598
38.4.9 TIMx capture/compare mode register 2 (TIMx_CCMR2)(x = 1, 8) . . 1601
38.4.10 TIMx capture/compare mode register 2 [alternate]
(TIMx_CCMR2)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1602
38.4.11 TIMx capture/compare enable register
(TIMx_CCER)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1604
38.4.12 TIMx counter (TIMx_CNT)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . 1607
38.4.13 TIMx prescaler (TIMx_PSC)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . 1607
38.4.14 TIMx auto-reload register (TIMx_ARR)(x = 1, 8) . . . . . . . . . . . . . . . . 1607
38.4.15 TIMx repetition counter register (TIMx_RCR)(x = 1, 8) . . . . . . . . . . . 1608
38.4.16 TIMx capture/compare register 1
(TIMx_CCR1)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1608
38.4.17 TIMx capture/compare register 2
(TIMx_CCR2)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1609
38.4.18 TIMx capture/compare register 3
(TIMx_CCR3)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1609
38.4.19 TIMx capture/compare register 4
(TIMx_CCR4)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1610
38.4.20 TIMx break and dead-time register
(TIMx_BDTR)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1610
38.4.21 TIMx DMA control register
(TIMx_DCR)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1613
38.4.22 TIMx DMA address for full transfer
(TIMx_DMAR)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1614
38.4.23 TIMx capture/compare mode register 3
(TIMx_CCMR3)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1615
38.4.24 TIMx capture/compare register 5
(TIMx_CCR5)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1616
38.4.25 TIMx capture/compare register 6
(TIMx_CCR6)(x = 1, 8) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1617
38.4.26 TIM1 alternate function option register 1 (TIM1_AF1) . . . . . . . . . . . . 1617
38.4.27 TIM1 Alternate function register 2 (TIM1_AF2) . . . . . . . . . . . . . . . . . 1619
38.4.28 TIM8 Alternate function option register 1 (TIM8_AF1) . . . . . . . . . . . . 1620
38.4.29 TIM8 Alternate function option register 2 (TIM8_AF2) . . . . . . . . . . . . 1622
38.4.30 TIM1 timer input selection register (TIM1_TISEL) . . . . . . . . . . . . . . . 1624
40/3353 RM0433 Rev 8

---

**AI Reasoning**: The content chunk provides detailed information about various TIMx registers, which are part of the technical specifications of the STM32H7 microcontrollers. Grouping this under 'specifications' makes it easy to locate for users looking for technical register details. The filename captures the essence of the content, focusing on the TIMx registers overview.
