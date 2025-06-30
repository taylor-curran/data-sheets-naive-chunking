# Decimation and Output Data Rate

**Source**: Page 25, Chunk 75  
**Category**: Decimation and Output Data Rate  
**Chunk Index**: 75

---

25 (53)
CONFIDENTIAL
5.4.2 Decimation
Certain systems need to utilize every available sample and for example acquire samples from all axis at
the same time instant. As the natural output data rate with nominal primary frequency is 11.8 kHz, this
can create excessive load for the MCU. The purpose of decimation is to decrease the internal update
rate to give the host system enough time to read every sample.
During start-up, the user can select a suitable decimation from the options presented in Table 15
Selectable decimation ratios and corresponding ODR. The selected decimation ratio is applied to
outputs RATE_XYZ2 and ACC_XYZ2.
Output data rate with nominal F_PRIM
Decimation factor Output data rate

---

**AI Reasoning**: The content discusses the concept of decimation and its impact on output data rate, which is a feature of the hardware. Placing it under 'features' makes it easily discoverable for users looking for functional aspects of the device. The filename captures the essence of the content by highlighting the main topics discussed.
