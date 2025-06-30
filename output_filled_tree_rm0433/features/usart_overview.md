# Overview of USART features and implementation

**Source**: Page 51, Chunk 225  
**Category**: Overview of USART features and implementation  
**Chunk Index**: 225

---

48.1 USART introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2018
48.2 USART main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2019
48.3 USART extended features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2020
48.4 USART implementation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2020
48.5 USART functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2021
48.5.1 USART block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2021
48.5.2 USART signals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2022
48.5.3 USART character description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2023
48.5.4 USART FIFOs and thresholds . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2025
48.5.5 USART transmitter . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2025
48.5.6 USART receiver . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2029
48.5.7 USART baud rate generation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2036
48.5.8 Tolerance of the USART receiver to clock deviation . . . . . . . . . . . . . 2037
48.5.9 USART auto baud rate detection . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2039
48.5.10 USART multiprocessor communication . . . . . . . . . . . . . . . . . . . . . . . 2041
48.5.11 USART Modbus communication . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2043
48.5.12 USART parity control . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2044
48.5.13 USART LIN (local interconnection network) mode . . . . . . . . . . . . . . 2045
48.5.14 USART synchronous mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2047
48.5.15 USART single-wire Half-duplex communication . . . . . . . . . . . . . . . . 2051
48.5.16 USART receiver timeout . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2051
48.5.17 USART Smartcard mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2052
48.5.18 USART IrDA SIR ENDEC block . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2056
48.5.19 Continuous communication using USART and DMA . . . . . . . . . . . . . 2059
RM0433 Rev 8 51/3353
70

---

**AI Reasoning**: The content chunk provides a comprehensive overview of the USART module, including its introduction, main and extended features, and detailed functional description. Grouping it under 'features' allows for easy access to information about the capabilities and functionalities of the USART, which is a key aspect of the microcontroller's features.
