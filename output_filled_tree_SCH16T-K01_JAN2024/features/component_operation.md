# Description of SCH16T component operation and startup sequence

**Source**: Page 21, Chunk 65  
**Category**: Description of SCH16T component operation and startup sequence  
**Chunk Index**: 65

---

5.1 Component operation
The SCH16T component has an internal power-on reset circuit. After release of EXTRESN and once
the power supplies are within the specified range, the component reads configuration and calibration
data from the non-volatile memory to volatile registers. After the memory is read, the sensor goes to low
power mode and an external SPI command, EN_SENSOR, is needed to continue to the initialization
phase and to start the measurement.
Start-up time is dependent on the low pass filter setting. After power-on or reset (release of EXTRESN
or EN_SENSOR command) the sensor shall be able to provide valid acceleration and angular rate data
after the specified power-on start-up time.
SCH16T uses LPF0 (68 Hz) low pass filter setting by default and the filter can be changed by SPI
command. SCH16T has extensive internal fault diagnostics to detect possible over range and internal
failures. Diagnostic status can be monitored via status bits included in SPI frame and status registers.
During the startup sequence, the sensor performs a series of internal tests that will set various error
flags in the sensor status registers. To clear them it is necessary to read the status registers after the

---

**AI Reasoning**: The content primarily describes the operation and startup sequence of the SCH16T component, including power-on reset, configuration, and diagnostics. This fits well under 'features' as it details the operational characteristics and capabilities of the component.
