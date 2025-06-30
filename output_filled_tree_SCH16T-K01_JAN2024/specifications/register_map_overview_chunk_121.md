# Register map overview and memory bank details

**Source**: Page 36, Chunk 121  
**Category**: Register map overview and memory bank details  
**Chunk Index**: 121

---

Table 25 Register map overview
Data Data Data Data
Adress 15h0000 15h0010 15h0020 15h0030
width width width width
4h0 Reserved - TEMP 16-bit Reserved - Reserved -
4h1 RATE_X1 20-bit RATE_DCNT 12-bit Reserved - Reserved -
4h2 RATE_Y1 20-bit ACC_DCNT 14-bit Reserved - Reserved -
4h3 RATE_Z1 20-bit FREQ_CNTR 16-bit Reserved - CTRL_USER 16-bit
_IF
4h4 ACC_X1 20-bit STAT_SUM 16-bit Reserved - CTRL_ST 13-bit
4h5 ACC_Y1 20-bit STAT_SUM_SAT 16-bit CTRL_FILT_RAT 9-bit CTRL_MOD 4-bit
E E
4h6 ACC_Z1 20-bit STAT_COM 16-bit CTRL_FILT_ACC 9-bit CTRL_RESE 4-bit
12 T
4h7 ACC_X3 20-bit STAT_RATE_COM 16-bit CTRL_FILT_ACC 9-bit SYS_TEST 16-bit
3
4h8 ACC_Y3 20-bit STAT_RATE_X 16-bit CTRL_RATE 15-bit SPARE_1 16-bit
4h9 ACC_Z3 20-bit STAT_RATE_Y 16-bit CTRL_ACC12 15-bit SPARE_2 16-bit
4hA RATE_X2 20-bit STAT_RATE_Z 16-bit CTRL_ACC3 3-bit SPARE_3 16-bit
4hB RATE_Y2 20-bit STAT_ACC_X 16-bit Reserved - ASIC_ID 12-bit
4hC RATE_Z2 20-bit STAT_ACC_Y 16-bit Reserved - COMP_ID 16-bit
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides a detailed overview of the register map, including memory banks, address offsets, and data widths. This information is best categorized under 'specifications' as it specifies the technical details of the hardware's register configuration.
