# I2S and SPI functionality and features

**Source**: Page 54, Chunk 231  
**Category**: I2S and SPI functionality and features  
**Chunk Index**: 231

---

50.8 I2S main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2192
50.9 I2S functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2193
50.9.1 I2S general description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2193
50.9.2 Pin sharing with SPI function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2193
50.9.3 Bitfields usable in I2S/PCM mode . . . . . . . . . . . . . . . . . . . . . . . . . . . 2194
50.9.4 Slave and master modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2195
50.9.5 Supported audio protocols . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2195
50.9.6 Additional Serial Interface Flexibility . . . . . . . . . . . . . . . . . . . . . . . . . 2201
50.9.7 Startup sequence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2203
50.9.8 Stop sequence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2205
50.9.9 Clock generator . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2205
50.9.10 Internal FIFOs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2208
50.9.11 FIFOs status flags . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2209
50.9.12 Handling of underrun situation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2209
50.9.13 Handling of overrun situation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2210
50.9.14 Frame error detection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2211
50.9.15 DMA Interface . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2212
50.9.16 Programing examples . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2214
50.10 I2S wakeup and interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2216
50.11 SPI/I2S registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2217
50.11.1 SPI/I2S control register 1 (SPI_CR1) . . . . . . . . . . . . . . . . . . . . . . . . 2217
50.11.2 SPI control register 2 (SPI_CR2) . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2219
50.11.3 SPI configuration register 1 (SPI_CFG1) . . . . . . . . . . . . . . . . . . . . . . 2219
50.11.4 SPI configuration register 2 (SPI_CFG2) . . . . . . . . . . . . . . . . . . . . . . 2222
50.11.5 SPI/I2S interrupt enable register (SPI_IER) . . . . . . . . . . . . . . . . . . . 2224
54/3353 RM0433 Rev 8

---

**AI Reasoning**: The content primarily discusses the features and functional description of the I2S interface, including its integration with SPI. It fits well under a 'features' category as it details the capabilities and operational aspects of these interfaces. The filename captures the essence of the content by highlighting the focus on I2S and SPI functionality.
