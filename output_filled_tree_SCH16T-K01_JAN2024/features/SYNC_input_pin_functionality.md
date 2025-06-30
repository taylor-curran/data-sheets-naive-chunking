# Description of the SYNC input pin and its functionality

**Source**: Page 25, Chunk 78  
**Category**: Description of the SYNC input pin and its functionality  
**Chunk Index**: 78

---

1.36 ms. This means that sample age can be anything between 0 and 1.36 ms. To address this issue,
the user can combine decimation with the data ready function. Data ready is explained in chapter 5.4.4.
5.4.3 SYNC input pin
Certain systems with high-performance requirements may benefit from use of multiple SCH16T
components. Depending on application SPI master clock conditions, the read operation of multiple
parallel sensors can take longer than sensor internal register update period if individual MISO line is not
used for each component. As a result of this, samples are being acquired from different time instants for
each parallel sensor. In certain real-world inputs, this can lead to a significant apparent disagreement of
sensors, as different time-instants are being sampled.
To mitigate this issue, SYNC input pin has been implemented. When the master issues SYNC signal to
all sensors in the system, the sensors' internal updates for RATE_XYZ1/2 and ACC_XYZ1/2/3 are
frozen until SYNC pin is set LOW, or after time out period set by CTRL_SYNC_TOC_TH time-out
counter. This allows enough time for the master to read all sensor data from a single time instant.
CTRL_SYNC_TOC_TH is user-selectable with typical values ranging from 1.2 ms to 11.6 ms. Please
refer to chapter 0 for user controls.
SYNC is only feasible on interpolated outputs RATE_XYZ1 and ACC_XYZ1/3. With decimated outputs
and a decimation factor of 2 or above, most masters should have enough time to read the output
registers before they are updated again.
SYNC can be beneficial also to ensure that all 6-axis data is captured at the same time instant. With
very low SPI master clocks, it can occur that even a single sensor will update its internal registers during
the slow read operation. In this case, different axis data could represent different time instant. SYNC
can also help in situations where system load is high, and sampling can not be performed with a
consistent frequency.
Please refer to illustration below.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content primarily discusses the SYNC input pin, its purpose, and how it can be used to synchronize sensor data acquisition. This fits well under 'features' as it describes a specific functionality of the hardware. The filename captures the essence of the content by focusing on the SYNC input pin.
