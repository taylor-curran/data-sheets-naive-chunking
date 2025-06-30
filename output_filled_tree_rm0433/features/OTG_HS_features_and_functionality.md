# Overview of OTG_HS features and functionality in host and peripheral modes

**Source**: Page 63, Chunk 254  
**Category**: Overview of OTG_HS features and functionality in host and peripheral modes  
**Chunk Index**: 254

---

57.2.2 Host-mode features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2592
57.2.3 Peripheral-mode features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2592
57.3 OTG_HS implementation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2593
57.4 OTG_HS functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2593
57.4.1 OTG_HS block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2593
57.4.2 OTG_HS pin and internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . 2595
57.4.3 OTG_HS core . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2595
57.4.4 Embedded full-speed OTG PHY connected to OTG_HS . . . . . . . . . 2596
57.4.5 OTG detections . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2596
57.4.6 High-speed OTG PHY connected to OTG_HS . . . . . . . . . . . . . . . . . 2596
57.5 OTG_HS dual role device (DRD) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2597
57.5.1 ID line detection . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2597
57.5.2 HNP dual role device . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2597
57.5.3 SRP dual role device . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2598
57.6 OTG_HS as a USB peripheral . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2598
57.6.1 SRP-capable peripheral . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2599
57.6.2 Peripheral states . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2599
57.6.3 Peripheral endpoints . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2600
57.7 OTG_HS as a USB host . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2602
57.7.1 SRP-capable host . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2603
57.7.2 USB host states . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2603
57.7.3 Host channels . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2605
57.7.4 Host scheduler . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2606
57.8 OTG_HS SOF trigger . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2607
RM0433 Rev 8 63/3353
70

---

**AI Reasoning**: The content chunk primarily discusses the features and functional aspects of the OTG_HS (On-The-Go High-Speed) interface, including its implementation, functional description, dual role device capabilities, and its operation as a USB host and peripheral. Grouping this under 'features' provides a broad yet relevant category that aligns with the content's focus on describing the capabilities and functionalities of the OTG_HS interface.
