# Synchronization features for asynchronous clock domains

**Source**: Page 23, Chunk 71  
**Category**: Synchronization features for asynchronous clock domains  
**Chunk Index**: 71

---

applications. The table below summarizes the synchronization features.
Table 14 Solutions for asynchronous clock domains
Feature Use case Value
Interpolation This should be used by default. Interpolation - Minimized sampling jitter
is applied in outputs RATE_XYZ1, - Minimized timing difference between channels
ACC_XYZ1, and ACC_XYZ3. - No missing samples
SYNC Input Special case. Recommended if there is a - Synchronization between multiple sensors.
need to sync between multiple SCH16T - Data can be received with consistent rate even
family sensors or if sample time consistency if host system sampling is affected by
is valued over jitter changing load
DRY Output (Data Special case. Recommended only if - Minimized sampling jitter. With decimated
Ready Interrupt) decimated, low update rate outputs outputs, the maximum data jitter depends on
RATE_XYZ2 and ACC_XYZ2 are used. the decimation ratio and interrupt use removes
Decimated outputs are typically used if MCU this jitter totally.
bandwidth is limited. - No missing samples.
Data counter Special case. Recommended only if Data - Data counter is index for the component data
Ready is not preferred in application. output values. The application can monitor
that:
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content discusses various synchronization features and their use cases for managing asynchronous clock domains, which fits well under the 'features' category. The filename 'synchronization_features.md' captures the essence of the content, making it easily discoverable.
