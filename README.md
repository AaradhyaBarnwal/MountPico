# MountPico
I have created a custom RP2040 development board with awesome graphics and two header for each GPIO pins. Why have I design this? Why not? It looks cool! and I learnt some of KiCad on the go.

### Image of PCB
<img width="694" height="632" alt="image" src="https://github.com/user-attachments/assets/ff346c75-074c-4c27-9178-6cb39532c7c9" />



## BOM
|Comment                    |Designator                      |Footprint                                  |JLCPCB Part #|
|---------------------------|--------------------------------|-------------------------------------------|-------------|
|33pF                       |C14,C15                         |0402                                       |C1562        |
|1uF                        |C1,C9                           |0402                                       |C52923       |
|1K                         |R5,R7                           |0402                                       |C11702       |
|0.1uF                      |C10,C11,C16,C2,C3,C4,C5,C6,C7,C8|0402                                       |C1525        |
|5.1K                       |R1,R2                           |0402                                       |C25905       |
|10K                        |R6                              |0402                                       |C25744       |
|NCP1117-3.3_SOT223         |U2                              |SOT-223-3_TabPin2                          |C26537       |
|100                        |R8                              |0402                                       |C25076       |
|LED                        |D1                              |0805                                       |C84256       |
|RP2040                     |U1                              |QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm        |C2040        |
|27                         |R3,R4                           |0402                                       |C25100       |
|W25Q128JVS                 |U3                              |Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm|C2843335     |
|12MHz                      |Y1                              |Crystal_SMD_3225-4Pin_3.2x2.5mm            |C481407      |
|USB_C_Receptacle_USB2.0_14P|J1                              |USB_C_Receptacle_HRO_TYPE-C-31-M-12        |C165948      |
|10uF                       |C12,C13                         |0603                                       |C19702       |
|SW_Push                    |SW1                             |SW_Push_SPST_NO_Alps_SKRK                  |C720477      |
|                           |                                |                                           |             |
|                           |Vendor                          |Price                                      |             |
|PCB Manufacturing          |JLCPCB                          |$4.00                                      |             |
|PCBA                       |JLCPCB                          |$48.08                                     |             |
|Shipping                   |                                |$22.99                                     |             |


## How to use 
Solder the PCB headers and then you can use it as a raspberry pi pico
