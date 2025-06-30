# Description of component output channels and their configurations

**Source**: Page 23, Chunk 68  
**Category**: Description of component output channels and their configurations  
**Chunk Index**: 68

---

23 (53)
CONFIDENTIAL
5.3 Component output channels
The SCH16T series component has several output channels for the user to choose from. The
component has two channels for reading gyroscope data and a total of 3 channels for reading
acceleration data. Each channel consists of separate X, Y and Z output data registers and each channel
and axis has separate status flags. The first gyroscope data channel RATE_XYZ1 has interpolated
output and the second channel RATE_XYZ2 is for decimated output. The first acceleration channel
ACC_XYZ1 has interpolated output, second channel ACC_XYZ2 is for decimated output and the third
channel is an auxiliary interpolated channel, ACC_XYZ3. Interpolation and decimation are explained in
more detail in 5.4.
The user may choose to utilize multiple channels simultaneously and adjust channel settings separately
according to the users’ needs. Dynamic range can be individually set for each channel, but filter settings
are shared between interpolated and decimated outputs. Different filters within one channel can be
applied between X-, Y- and Z-axis, if desired. For example, the user can read ACC_XYZ1 with nominal
±163.4 m/s2 dynamic range and 68 Hz filter, and ACC_XYZ3 with nominal ±20.48 m/s2 dynamic range
and 13 Hz filter. The output options are presented in the table below.
Dynamic range
Channel Description Filter setting

---

**AI Reasoning**: The content primarily describes the output channels of the SCH16T component, detailing their configurations and options. This fits well under 'features' as it highlights the capabilities and settings available for the component's output channels. The filename captures the essence of the content by focusing on the description of output channels.
