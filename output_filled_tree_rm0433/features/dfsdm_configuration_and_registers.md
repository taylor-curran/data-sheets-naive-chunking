# DFSDM configuration and register details

**Source**: Page 29, Chunk 176  
**Category**: DFSDM configuration and register details  
**Chunk Index**: 176

---

RM0433 Contents
30.4.4 Serial channel transceivers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1124
30.4.5 Configuring the input serial interface . . . . . . . . . . . . . . . . . . . . . . . . . 1134
30.4.6 Parallel data inputs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1134
30.4.7 Channel selection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1136
30.4.8 Digital filter configuration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1137
30.4.9 Integrator unit . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1138
30.4.10 Analog watchdog . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1139
30.4.11 Short-circuit detector . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1141
30.4.12 Extreme detector . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1142
30.4.13 Data unit block . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1142
30.4.14 Signed data format . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1143
30.4.15 Launching conversions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1144
30.4.16 Continuous and fast continuous modes . . . . . . . . . . . . . . . . . . . . . . . 1144
30.4.17 Request precedence . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1145
30.4.18 Power optimization in run mode . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1146
30.5 DFSDM interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .1146
30.6 DFSDM DMA transfer . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .1148
30.7 DFSDM channel y registers (y=0..7) . . . . . . . . . . . . . . . . . . . . . . . . . . .1148
30.7.1 DFSDM channel y configuration register (DFSDM_CHyCFGR1) . . . 1148
30.7.2 DFSDM channel y configuration register (DFSDM_CHyCFGR2) . . . 1150
30.7.3 DFSDM channel y analog watchdog and short-circuit detector register
(DFSDM_CHyAWSCDR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1151
30.7.4 DFSDM channel y watchdog filter data register
(DFSDM_CHyWDATR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1152
30.7.5 DFSDM channel y data input register (DFSDM_CHyDATINR) . . . . . 1152
30.8 DFSDM filter x module registers (x=0..3) . . . . . . . . . . . . . . . . . . . . . . . .1153
30.8.1 DFSDM filter x control register 1 (DFSDM_FLTxCR1) . . . . . . . . . . . 1153
30.8.2 DFSDM filter x control register 2 (DFSDM_FLTxCR2) . . . . . . . . . . . 1156
30.8.3 DFSDM filter x interrupt and status register (DFSDM_FLTxISR) . . . . 1157
30.8.4 DFSDM filter x interrupt flag clear register (DFSDM_FLTxICR) . . . . 1159
30.8.5 DFSDM filter x injected channel group selection register
(DFSDM_FLTxJCHGR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1160
30.8.6 DFSDM filter x control register (DFSDM_FLTxFCR) . . . . . . . . . . . . . 1160
30.8.7 DFSDM filter x data register for injected group
(DFSDM_FLTxJDATAR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1161
30.8.8 DFSDM filter x data register for the regular channel
(DFSDM_FLTxRDATAR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1162
RM0433 Rev 8 29/3353
70

---

**AI Reasoning**: The content chunk primarily discusses various aspects of configuring the DFSDM (Digital Filter for Sigma-Delta Modulators) and its associated registers. This fits well under 'features' as it describes specific functionalities and configurations of the microcontroller. The filename captures the essence of the content by highlighting both configuration and register details, making it easily discoverable.
