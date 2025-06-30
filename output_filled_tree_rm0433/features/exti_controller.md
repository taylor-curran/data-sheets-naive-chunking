# Extended interrupt and event controller (EXTI) features and functionality

**Source**: Page 19, Chunk 146  
**Category**: Extended interrupt and event controller (EXTI) features and functionality  
**Chunk Index**: 146

---

20.1 EXTI main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 758
20.2 EXTI block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 758
20.2.1 EXTI connections between peripherals, CPU, and D3 domain . . . . . . 759
20.3 EXTI functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 760
20.3.1 EXTI Configurable event input CPU wakeup . . . . . . . . . . . . . . . . . . . . 761
20.3.2 EXTI configurable event input Any wakeup . . . . . . . . . . . . . . . . . . . . . 762
20.3.3 EXTI direct event input CPU wakeup . . . . . . . . . . . . . . . . . . . . . . . . . 764
20.3.4 EXTI direct event input Any wakeup . . . . . . . . . . . . . . . . . . . . . . . . . . 765
20.3.5 EXTI D3 pending request clear selection . . . . . . . . . . . . . . . . . . . . . . 766
20.4 EXTI event input mapping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 766
20.5 EXTI functional behavior . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 769
20.5.1 EXTI CPU interrupt procedure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 770
20.5.2 EXTI CPU event procedure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 770
20.5.3 EXTI CPU wakeup procedure . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 771
20.5.4 EXTI D3 domain wakeup for autonomous Run mode procedure . . . . 771
RM0433 Rev 8 19/3353
70

---

**AI Reasoning**: The content chunk is focused on the features and functional description of the EXTI (Extended Interrupt and Event Controller), which is a specific feature of the STM32 microcontrollers. Placing it under 'features' makes it easily discoverable for users looking for detailed information on specific functionalities of the hardware. The filename 'exti_controller.md' succinctly captures the essence of the content.
