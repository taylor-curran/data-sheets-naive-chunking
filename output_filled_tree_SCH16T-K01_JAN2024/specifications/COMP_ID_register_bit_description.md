# Description of the COMP_ID register and serial number format

**Source**: Page 50, Chunk 194  
**Category**: Description of the COMP_ID register and serial number format  
**Chunk Index**: 194

---

Table 76 COMP_ID register bit description
Bit Name Bit Description Bits
COMP_ID Component version. e.g., SCH16T-K01 [15:0]
The component shall be traceable by a unique electronically readable serial number.
Serial number string format: DDDYYFHHHHH0X
Serial number is stored in NVM registers SN_ID1, SN_ID2 and SN_ID3.
H0 is a fixed value and therefore not stored to NVM.
SN_ID1 [3:0] content corresponds to “F” part of serial number (4bit hex to string, 0...F)
Example register content: 0000, therefore 0
SN_ID1 [6:4] content corresponds to “X” part of serial number (3bit hex to string, 0…7) determining product series.
For SCH16T Series the serial number ending is fixed to 1 and SN_ID1 [6:4] content is left as ‘0’
SN_ID2 [15:0] content corresponds to “DDDYY” part of serial number (16bit unsigned integer to decimal
string, 0....65535)
Example register content: 1000 1010 0101 1111, therefore 35423
SN_ID3 [15:0] content corresponds to “HHHH” part of serial number (16bit hexadecimal running
number)
Example: 0001 0100 1001 0111
0001 = 1
0100 = 4
1001 = 9
0111 = 7
, therefore 1497
Final serial number result will be 3542301497H01
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content provides detailed information about the COMP_ID register and the format of the serial number, which are key specifications of the component. Placing it under 'specifications' makes it easily accessible for those looking for technical details about the component's identification and versioning.
