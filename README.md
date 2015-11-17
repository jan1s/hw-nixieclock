# hw-nixieclock-mini
This is work in progress


## PCBs

The clock has seperate control and display pcbs. Those pcbs do not only form a basic case for the electronics, but also allow for flexible use with different tubes.

![Control PCB](../top_control_rev_a.png "Control PCB") 

![Display PCB for ZM1325](../top_display_zm1325_rev_a.png "Display PCB for ZM1325") 


## BOM
| Identifier | Type/Value | Quantity | [Reichelt][reichelt] | [Digikey][digikey] | Comment |
| :---        | :---        | :---      | :---         | :---      | :---     |
| R1, R2, R3, R4 | 33 Ω | 4 | SMD-0603 33 | 311-33GRCT-ND |
| R12, R13 | 1 kΩ | 2 | SMD-0603 1,00K | 311-1.0KGRCT-ND |
| C1, C2, C13, C14 | 22 pF | 4 | NPO-G0603 22P |  |
| C7, C8 | 10 nF | 4 | X7R-G0603 10N |  |
| C18, C19, C20, C21 | 100 nF | 4 | X7R-G0603 100N |  |
| C3, C5, C6, C10, C11 | 10 µF | 5 | X5R-G0603 10/6 |  |
| L1 | Ferrite Bead | 1 | BLM18AG 121 | 490-1011-1-ND |
| Y1 | 8MHz | 1 | - | 535-10630-1-ND |
| Y2 | 32kHz | 1 | 32,768 PGD-9 | 535-9542-1-ND |
| LED1 | LED green | 1 | LG L29K |  |
| LED2 | LED white | 1 | LW L283 | |
| BAT1 | Batteryholder | 1 | - | BC501SM-ND |
| BAT | CR 1220 | 1 | CR 1220 VAR | SY033-ND |
| SW1 | Tact Switch Top | 1 | - | EG2531CT-ND |
| J1 | 2x5 Socket | 1 | - | A100866TR-ND, S5714-ND |
| J2 | USB Jack | 1 | USB BWM SMD | 151-1206-1-ND |
| IC1 | STM32F103C8T6 | 1 | STM32 F103C8T6 | 497-6063-ND |
| IC2, IC6 | LP2985 | 1 | LP 2985 IM5-3,3 |  |
| IC3, IC4 | USBLC6-2 | 1 | - | 497-5235-1-ND |

## Power supply - BOM
| Identifier | Type/Value | Quantity | [Reichelt][reichelt] | [Digikey][digikey] | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R23 | 0.01 Ω | 1 | - | RHM.10MCT-ND |
| R18 | 82 kΩ | 1 | SMD-0603 82K |  |
| R20 | 8,2 kΩ | 1 | SMD-0603 8,2K | [Reichelt][reichelt] |
| R19 | 1 MΩ | 1 | SMD-1206 1M | [Reichelt][reichelt] |
| C12 | 150 pF | 1 | NPO-G0603 150P | [Reichelt][reichelt] |
| C9 | 22 nF | 2 | X7R-G0603 22N | [Reichelt][reichelt] |
| C4 | 1 µF / 250V | 1 | 1u/250V |  | 490-3550-1-ND |
| C15, C16 | 10 µF | 2 | X5R-G0603 10/6 |  |
| C17 | 100 µF | 1 | X5R-G1210 100 |  |
| D2 | Diode | 1 | BAT 54C SMD |  |
| D3 | Diode | 1 | XXX |  |
| L2 | 680 µH | 1 | L-PISR 680µ |  |
| T1 | IRF 7470 | 1 | IRF 7470 | IRF7470PBFCT-ND |
| IC5 | LT1619ES8 | 1 | - | LT1619ES8#PBF-ND |

## Display Board - BOM
| Identifier | Type/Value | Quantity | [Reichelt][reichelt] | [Digikey][digikey] | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R1-R4 | 220 kΩ | 4 | SMD-0603 220K | [Reichelt][reichelt] |
| R10-R60 | 22 kΩ | 4 | SMD-0603 22K | [Reichelt][reichelt] |
| RN10-RN71| 4x10 kΩ | 12 | BCN16 10K | [Reichelt][reichelt] |
| C1-C8 | 100 nF | 6 | X7R-G0603 100N | [Reichelt][reichelt] |
| T1-T69 | SMBTA 42 SMD | 42 | SMBTA 42 SMD | SMBTA42E6327INCT-ND |
| IC1-IC8 | 74HC595PW | 6 |  | 568-2263-1-ND |
| JP1 | 2x5pol Header | 1 | ??? | 609-4723-ND |
| GL1, GL2 | Neon Bulb | 2 | GLIMMLAMPE | C2A-ND |

[reichelt]: http://www.reichelt.de
[digikey]: http://www.digikey.de
[mouser]: http://mouser.com
[aliexpress]: http://www.aliexpress.com
