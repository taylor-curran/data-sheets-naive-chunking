# Description of SPI frame status bits and error reporting

**Source**: Page 31, Chunk 97  
**Category**: Description of SPI frame status bits and error reporting  
**Chunk Index**: 97

---

Table 19 Status bit description
Status bits S[1:0] Description
00 Normal operation
01 Error status
10 Saturation error
11 Initialization running
S[1:0] priority order is 11 (Initialization) --> 01 (Error) -->10 (Saturation) --> 00 (Normal operation)
Note that the Status bits S[1:0] are always '00' on the response frame for register write commands.
IDS, or Internal Data Status bit is redundant error status bit for S[1:0] in case of common status error.
0 - Normal Operation
1 - Common Error
CE status bit reports Command Errors.
0 - Normal Operation
1 - Command Error
The following access errors are detected and reported:
• Write request when EOI is active, excluding write to reset activation register.
• Read or write to SPI_TMODE addresses when SPI_TMODE is inactive. (Factory only)
• Read or write request to unused/undefined address.
• Write request to read-only register.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content primarily describes the status bits related to the SPI frame, including their meanings and priority order. It also covers error reporting mechanisms. This fits well under 'specifications' as it details specific operational characteristics of the hardware.
