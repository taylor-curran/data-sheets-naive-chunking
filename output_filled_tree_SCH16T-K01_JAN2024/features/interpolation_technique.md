# Description of interpolation technique to minimize sampling jitter

**Source**: Page 24, Chunk 73  
**Category**: Description of interpolation technique to minimize sampling jitter  
**Chunk Index**: 73

---

5.4.1 Interpolation
The purpose of interpolation is to minimize time uncertainty (sampling jitter) by increasing artificially the
internal sample rate. The natural output data rate of all data outputs is F_PRIM/2, which is 11.8 kHz
with nominal primary frequency. This means that a time-uncertainty between sensor register update and
system sampling time could be theoretically anything between 0...85 µs.
To minimize this jitter, a fixed interpolation factor of 32 is applied to outputs RATE_XYZ1, ACC_XYZ1,
and ACC_XYZ3. With nominal primary frequency it corresponds to a 377.6 kHz refresh rate of register
content.
The sample rate is increased by adding a one(1) cycle latency delay to the initial sample. The delay
corresponds to the maximum time uncertainty which with nominal primary frequency is 85 µs. A linear
interpolation is then applied between the initial sample and the new sample, and this interpolation is
divided into time segments by the artificially increased update rate 32 x F_PRIM/2. Time uncertainty is
now reduced to the length of this segment, which is max (85 µs)/32 = 2.6 µs (with nominal primary
frequency).
Please refer to illustration below.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content discusses a specific feature of the hardware related to interpolation to reduce time uncertainty in sampling. It fits well under 'features' as it describes a technical method used in the device. The filename captures the essence of the content, focusing on the interpolation technique.
