# RTC features and functional description

**Source**: Page 49, Chunk 220  
**Category**: RTC features and functional description  
**Chunk Index**: 220

---

RM0433 Contents
46.2 RTC main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1905
46.3 RTC functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1905
46.3.1 RTC block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1905
46.3.2 RTC pins and internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1908
46.3.3 GPIOs controlled by the RTC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1908
46.3.4 Clock and prescalers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1910
46.3.5 Real-time clock and calendar . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1911
46.3.6 Programmable alarms . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1911
46.3.7 Periodic auto-wake-up . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1911
46.3.8 RTC initialization and configuration . . . . . . . . . . . . . . . . . . . . . . . . . . 1912
46.3.9 Reading the calendar . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1914
46.3.10 Resetting the RTC . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1915
46.3.11 RTC synchronization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1915
46.3.12 RTC reference clock detection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1916
46.3.13 RTC smooth digital calibration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1916
46.3.14 Time-stamp function . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1918
46.3.15 Tamper detection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1919
46.3.16 Calibration clock output . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1921
46.3.17 Alarm output . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1922
46.4 RTC low-power modes . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1922
46.5 RTC interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1922
46.6 RTC registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1923
46.6.1 RTC time register (RTC_TR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1923
46.6.2 RTC date register (RTC_DR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1924
46.6.3 RTC control register (RTC_CR) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1926
46.6.4 RTC initialization and status register (RTC_ISR) . . . . . . . . . . . . . . . . 1929
46.6.5 RTC prescaler register (RTC_PRER) . . . . . . . . . . . . . . . . . . . . . . . . 1932
46.6.6 RTC wake-up timer register (RTC_WUTR) . . . . . . . . . . . . . . . . . . . . 1933
46.6.7 RTC alarm A register (RTC_ALRMAR) . . . . . . . . . . . . . . . . . . . . . . . 1934
46.6.8 RTC alarm B register (RTC_ALRMBR) . . . . . . . . . . . . . . . . . . . . . . . 1935
46.6.9 RTC write protection register (RTC_WPR) . . . . . . . . . . . . . . . . . . . . 1936
46.6.10 RTC sub second register (RTC_SSR) . . . . . . . . . . . . . . . . . . . . . . . . 1936
46.6.11 RTC shift control register (RTC_SHIFTR) . . . . . . . . . . . . . . . . . . . . . 1937
46.6.12 RTC timestamp time register (RTC_TSTR) . . . . . . . . . . . . . . . . . . . . 1938
46.6.13 RTC timestamp date register (RTC_TSDR) . . . . . . . . . . . . . . . . . . . 1939
46.6.14 RTC time-stamp sub second register (RTC_TSSSR) . . . . . . . . . . . . 1940
RM0433 Rev 8 49/3353
70

---

**AI Reasoning**: The content chunk primarily discusses the features and functional description of the RTC (Real-Time Clock) module, including its main features, functional description, low-power modes, interrupts, and registers. Grouping this under 'features' makes it easily discoverable for users looking for detailed information about the RTC's capabilities and functionalities.
