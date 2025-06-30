# Calibration and operation details of the sensor

**Source**: Page 21, Chunk 64  
**Category**: Calibration and operation details of the sensor  
**Chunk Index**: 64

---

21 (53)
CONFIDENTIAL
Sensors are calibrated over temperature in three measurement points at -40 °C, +25 °C, and +110 °C.
Offset and sensitivity are calibrated with 2nd order polynomial and cross-axis with linear function.
Calibration variables are stored in non-volatile memory during manufacturing and are read automatically
during the start-up.
It should be noted that PCB assembly can cause offset errors to the sensor output. If possible, system-
level offset calibration (zeroing) after assembly is recommended.
5 Component operation, reset and power-up
The SCH16T component has an internal power-on reset circuit. After release of EXTRESN and once
the power supplies are within the specified range, the component reads configuration and calibration

---

**AI Reasoning**: The content primarily discusses the calibration process and operational aspects of the sensor, including temperature calibration points, offset errors, and power-up procedures. These details are best categorized under 'features' as they describe key functional characteristics of the sensor.
