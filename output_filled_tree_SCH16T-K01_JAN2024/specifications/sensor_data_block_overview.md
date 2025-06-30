# Overview of sensor data block registers and descriptions

**Source**: Page 37, Chunk 124  
**Category**: Overview of sensor data block registers and descriptions  
**Chunk Index**: 124

---

Table 26 Overview of sensor data block
Register
Register Description R/RW Public addr
Name
RATE_X1 Output, x-axis gyroscope, interpolation, common low pass filter with RATE_X2 R 15h0001,
D1
RATE_Y1 Output, y-axis gyroscope, interpolation, common low pass filter with RATE_Y2 R 15h0002,
D1
RATE_Z1 Output, z-axis gyroscope, interpolation, common low pass filter with RATE_Z2 R 15h0003,
D1
ACC_X1 Output, x-axis accelerometer, interpolation, common low pass filter with ACC_X2 R 15h0004,
D1
ACC_Y1 Output, y-axis accelerometer, interpolation, common low pass filter with ACC_Y2 R 15h0005,
D1
ACC_Z1 Output, z-axis accelerometer, interpolation, common low pass filter with ACC_Z2 R 15h0006,
D1
ACC_X3 Output, x-axis accelerometer, auxiliary signal path with interpolation and individually R 15h0007,
configurable low pass filter setting. D1
ACC_Y3 Output, y-axis accelerometer, auxiliary signal path with interpolation and individually R 15h0008,
configurable low pass filter setting. D1
ACC_Z3 Output, z-axis accelerometer, auxiliary signal path with interpolation and individually R 15h0009,
configurable low pass filter setting. D1
RATE_X2 Output, x-axis gyroscope, configurable decimation filter, common low pass filter with R 15h000A,
RATE_Y2 Output, y-axis gyroscope, configurable decimation filter, common low pass filter with R 15h000B,

---

**AI Reasoning**: The content provides detailed information about sensor data block registers, including their descriptions and addresses. This fits well under 'specifications' as it specifies the technical details of the sensor data block. The filename captures the essence of the content by highlighting the overview nature of the sensor data block.
