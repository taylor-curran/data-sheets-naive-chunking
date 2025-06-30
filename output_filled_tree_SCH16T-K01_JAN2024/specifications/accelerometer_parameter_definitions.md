# Definitions and descriptions of accelerometer parameters

**Source**: Page 9, Chunk 45  
**Category**: Definitions and descriptions of accelerometer parameters  
**Chunk Index**: 45

---

9 (53)
Table 7 Accelerometer parameter definitions
Symbol Description
Measurement range is tied to electrical headroom and is selectable from predefined options presented in 7.4.2.
A)
Changing electrical headroom affects only signal path sensitivity (up to 4*nominal sensitivity).
B) Initial offset at Murata production measurement after calibration
Offset drift over temperature is determined by ((maximum offset over temperature) - (minimum offset over
C)
temperature)) / 2 in condition of one temperature sweep in specified temperature range.
Estimated from offset drift during 1000 hours of high temperature operating life (HTOL) test at 125 °C and maximum
D)
supply voltages.
Default sensitivity used in factory calibration. With this default sensitivity, signal has a typical electrical headroom of
E)
±163.4 m/s2.
𝐴𝐶𝐶 (𝑎 )−𝐴𝐶𝐶 (𝑎 )
𝑆𝑒𝑛𝑠𝑖𝑡𝑖𝑣𝑖𝑡𝑦= 𝑚𝑒𝑎𝑠 +1𝑔 𝑚𝑒𝑎𝑠 −1𝑔
𝑎 −𝑎
+1𝑔 −1𝑔
Where:
a = applied acceleration at +1g (i.e., +1g gravity of manufacturing location)
F) +1g
a = applied acceleration at -1g (i.e., -1g gravity of manufacturing location)
-1g
ACC (a) = measured acceleration at a [LSB]
meas n n
Sensitivity drift over temperature is determined by [(maximum sensitivity value over temperature) - (minimum
sensitivity value over temperature)] / 2 *100%
Estimated from sensitivity drift during 1000 hours of high temperature operating life (HTOL) test at 125 °C and
G)
maximum supply voltages.
Linearity error is the residual error remaining after a least-squares linear fit over measurement range. (Best fit linear
H)
model)
I) Velocity random walk is the white noise term estimated from Allan deviation at tau = 1s
Allan variance minimum divided by 0.664. Optimization for SPI duty cycle or sample rate is required to achieve
J) typical Allan variance in table. Device powered on for four hours before data collection starts to permit full thermal
stabilization.
K) ACC axes are orthogonal if their intersecting angle is exactly 90°. Orthogonality error is the deviation from 90°.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides detailed definitions and descriptions of various accelerometer parameters, which are typically part of the specifications of a hardware component. Placing it under 'specifications' makes it easy to find for users looking for technical details about the accelerometer's performance and characteristics.
