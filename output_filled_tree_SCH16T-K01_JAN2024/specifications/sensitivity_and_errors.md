# Details on sensitivity, drift, and error metrics

**Source**: Page 7, Chunk 41  
**Category**: Details on sensitivity, drift, and error metrics  
**Chunk Index**: 41

---

𝐴𝑅 (𝛺 )−𝐴𝑅 (𝛺 )
𝑆𝑒𝑛𝑠𝑖𝑡𝑖𝑣𝑖𝑡𝑦= 𝑚𝑒𝑎𝑠 𝑚𝑎𝑥 𝑚𝑒𝑎𝑠 𝑚𝑖𝑛
𝛺 −𝛺
𝑚𝑎𝑥 𝑚𝑖𝑛
Where:
Ω = applied angular rate at maximum operating range
F) max
Ω = applied angular rate at minimum operating range
min
AR (Ω) = measured angular rate at Ω [LSB]
meas n n
Sensitivity drift over temperature is determined by [(maximum sensitivity value over temperature) - (minimum
sensitivity value over temperature)] / 2 *100%
Estimated from sensitivity drift during 1000 hours of high temperature operating life (HTOL) test at 125 °C and
G)
maximum supply voltages.
Linearity error is the residual error remaining after a least-squares linear fit over measurement range. (Best fit linear
H)
model)
I) Angle random walk is the white noise term estimated from Allan deviation at tau = 1s
Allan variance minimum divided by 0.664. Optimization for SPI duty cycle or sample rate is required to achieve
J) typical Allan variance in table. Device is powered on for four hours before data collection starts to permit full thermal
stabilization.
K) Rate axes are orthogonal if their intersecting angle is exactly 90°. Orthogonality error is the deviation from 90°.
Angular rate offset sensitivity in respect to orientation in the earth gravitation. Contains 0.004 °/s from Earth’s
L)
rotation. Can not be extrapolated beyond gravitation.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content primarily discusses sensitivity calculations, sensitivity drift, linearity error, and other error metrics related to the device's performance. These are technical specifications that define how the device behaves under certain conditions, making 'specifications' the most appropriate category. The filename captures the essence of the content by focusing on sensitivity and error metrics.
