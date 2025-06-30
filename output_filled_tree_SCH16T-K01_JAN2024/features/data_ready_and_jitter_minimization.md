# Data ready signal and jitter minimization in sensor data reading

**Source**: Page 26, Chunk 80  
**Category**: Data ready signal and jitter minimization in sensor data reading  
**Chunk Index**: 80

---

5.4.4 Data ready, DRY
In some system implementations, it may be that the rate at which the host processor can read the
peripherals is limited. In these cases, to ensure that the host has enough time to read without signal
aliasing it is beneficial to use decimated outputs with suitable decimation factor. When the sensor
update rate is lowered by decimation, sampling jitter becomes more of an issue. As explained in chapter
is increased, the worst-case sampling jitter is increased accordingly.
In case jitter minimization is critical in application, user should use the data ready output pin

---

**AI Reasoning**: The content discusses the use of the data ready signal and considerations for minimizing jitter when reading sensor data, which are features related to the operation and performance of the hardware. Placing it under 'features' makes it easily discoverable for users looking for operational characteristics.
