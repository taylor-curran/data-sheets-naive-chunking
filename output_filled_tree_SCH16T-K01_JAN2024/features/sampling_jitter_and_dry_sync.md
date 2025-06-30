# Discussion on sampling jitter and data ready synchronization

**Source**: Page 26, Chunk 81  
**Category**: Discussion on sampling jitter and data ready synchronization  
**Chunk Index**: 81

---

5.4.1, worst case sampling jitter can be up to 85 µs with decimation factor of 1. When decimation factor
is increased, the worst-case sampling jitter is increased accordingly.
In case jitter minimization is critical in application, user should use the data ready output pin
(DRY_SYNC). When all sensor output channels have been updated, the data ready triggers a rising
edge to indicate that the samples were generated. This rising edge can be used as a direct interrupt to
start sensor read operation, or the host can take note of the data ready signal and ensure that the data
is read in a burst before the next expected sensor internal update. This way the system can ensure that
no samples are missed, and no samples are being read twice.
Please refer to illustration below.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content discusses the behavior of sampling jitter and the use of the data ready output pin (DRY_SYNC) to manage it. This is a feature of the sensor, as it describes how to handle specific operational characteristics. Placing it under 'features' makes it easily discoverable for users looking for operational details and functionalities.
