# Detailed features and implementation of the CRYP cryptographic processor

**Source**: Page 34, Chunk 188  
**Category**: Detailed features and implementation of the CRYP cryptographic processor  
**Chunk Index**: 188

---

35.2 CRYP main features . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1263
35.3 CRYP implementation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1264
35.4 CRYP functional description . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1265
35.4.1 CRYP block diagram . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1265
35.4.2 CRYP internal signals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1266
35.4.3 CRYP DES/TDES cryptographic core . . . . . . . . . . . . . . . . . . . . . . . . 1266
35.4.4 CRYP AES cryptographic core . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1267
35.4.5 CRYP procedure to perform a cipher operation . . . . . . . . . . . . . . . . . 1273
35.4.6 CRYP busy state . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1275
35.4.7 Preparing the CRYP AES key for decryption . . . . . . . . . . . . . . . . . . . 1276
35.4.8 CRYP stealing and data padding . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1276
35.4.9 CRYP suspend/resume operations . . . . . . . . . . . . . . . . . . . . . . . . . . 1278
35.4.10 CRYP DES/TDES basic chaining modes (ECB, CBC) . . . . . . . . . . . 1279
35.4.11 CRYP AES basic chaining modes (ECB, CBC) . . . . . . . . . . . . . . . . . 1284
35.4.12 CRYP AES counter mode (AES-CTR) . . . . . . . . . . . . . . . . . . . . . . . . 1289
35.4.13 CRYP AES Galois/counter mode (GCM) . . . . . . . . . . . . . . . . . . . . . . 1293
35.4.14 CRYP AES Galois message authentication code (GMAC) . . . . . . . . 1298
35.4.15 CRYP AES Counter with CBC-MAC (CCM) . . . . . . . . . . . . . . . . . . . 1299
35.4.16 CRYP data registers and data swapping . . . . . . . . . . . . . . . . . . . . . . 1304
35.4.17 CRYP key registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1308
35.4.18 CRYP initialization vector registers . . . . . . . . . . . . . . . . . . . . . . . . . . 1308
35.4.19 CRYP DMA interface . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1309
35.4.20 CRYP error management . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1311
35.5 CRYP interrupts . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1312
35.6 CRYP processing time . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1313
35.7 CRYP registers . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1314
35.7.1 CRYP control register (CRYP_CR) . . . . . . . . . . . . . . . . . . . . . . . . . . 1314
35.7.2 CRYP status register (CRYP_SR) . . . . . . . . . . . . . . . . . . . . . . . . . . . 1316
35.7.3 CRYP data input register (CRYP_DIN) . . . . . . . . . . . . . . . . . . . . . . . 1317
35.7.4 CRYP data output register (CRYP_DOUT) . . . . . . . . . . . . . . . . . . . . 1317
35.7.5 CRYP DMA control register (CRYP_DMACR) . . . . . . . . . . . . . . . . . . 1318
35.7.6 CRYP interrupt mask set/clear register (CRYP_IMSCR) . . . . . . . . . . 1319
35.7.7 CRYP raw interrupt status register (CRYP_RISR) . . . . . . . . . . . . . . 1319
35.7.8 CRYP masked interrupt status register (CRYP_MISR) . . . . . . . . . . . 1320
34/3353 RM0433 Rev 8

---

**AI Reasoning**: The content chunk provides an in-depth look at the CRYP cryptographic processor, including its features, implementation, functional description, and registers. This aligns well with a 'features' category, as it describes the capabilities and functionalities of the CRYP module. The filename captures the essence of the content by highlighting the focus on the CRYP processor.
