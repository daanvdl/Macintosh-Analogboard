# Macintosh 128K/512K/Plus Analogboard recreation

This is a tested and working analog board recreation of the Macintosh 128k/512k/Plus, 820-0107-D analog board. The provided files are licensed under CC-BY-NC-SA - they are NOT intended for commercial use

## General

This board can replace any revision (A/B/C) board. This INTERNATIONAL board can be configured for both 110V as 240V. I did **not** test the 110V setup. The 110V setup likely need component changes and has no documentation (yet).

## Improvements
* C1 3.9uF filmcap possibility
* All resistors, diodes and most of the capacitors are value labeled on silkscreen
* If a part no longer exists and there is a alternative, the replacement part is printed on silkscreen
* Some alternatives are described in the BOM in the comment row

## JLCPCB

This board can be produced using JLCPCB using 2MM thickness, but 1.6MM should also work. In general, a thicker PCB can offer better heat dissipation compared to a thinner one. A thicker PCB provides more material for heat to spread out and dissipate, potentially leading to lower temperatures in the components mounted on the board.

## BOM

This is a BOM for the **820-0107-D** INTERNATIONAL board in 240V setup. 
**Although I have done my utmost to ensure an accurate list, I cannot rule out that there are errors in the BOM. Use at your own risk*

| ID   | Value                          | Comment                                         |
| ---- | ------------------------------ | ----------------------------------------------- |
| B1   | Battery socket                 | https://airtalk.shop/product/macintosh-battery/ |
| C1   | 3.9/25V BP                     | Replacement: Panasonic ECQ-E1395JFW             |
| C2   | 4700/16V                       | 4700uF 16V                                      |
| C3   | 220/16V                        | 220uF  16V                                      |
| C4   | 0.033uF 400V ceramic disk      |                                                 |
| C5   | 47/10V                         | 47uF  10V                                       |
| C6   | 22/50V                         | 22uF 50V                                        |
| C7   | 0.01uF 1kV  ceramic disk       |                                                 |
| C8   | 0.01uF 1kV caramic disk        |                                                 |
| C9   | 0.22uF 100V  ceramic disk      |                                                 |
| C10  | 33/16V                         | 33uF 16V                                        |
| C11  | 10/160V                        | 10uF  160V                                      |
| C12  | 22/50V                         | 22uF 50V                                        |
| C13  | 0.01uF 1.5kV  ceramic disk     |                                                 |
| C14  | 0.01uF 1.5kV ceramic disk      |                                                 |
| C15  | 0.01uF 1.5kV  ceramic disk     |                                                 |
| C16  | 0.01uF 400V film               |                                                 |
| C17  | 0.01uF 400V  film              |                                                 |
| C18  | 33/16V                         | 33uF 16V                                        |
| C19  | 0.1uF                          | 0.1uF  ceramic axial                            |
| C20  | 0.1uF ceramic axial            |                                                 |
| C21  | 0.01uF 400V  film              |                                                 |
| C22  | 0.1uF 100V film                |                                                 |
| C23  | 0.1uF                          | 0.1uF  ceramic axial                            |
| C24  | 2200/16V                       | 2200uF 16V                                      |
| C25  | 0.022uF 400V  film             |                                                 |
| C26  | 0.1uF                          | 0.1uF caramic axial                             |
| C27  | 2200/10V                       | 2200uF  10V                                     |
| C28  | 1000/16V                       | 1000uF 16V                                      |
| C29  | 0.47uF 400V                    |                                                 |
| C30  | 2200/10V                       | 2200uF 10V                                      |
| C31  | 220/16V                        | 220uF  16V                                      |
| C32  | 2200/16V                       | 2200uF 16V                                      |
| C33  | 4.7nF                          | 4700pf  250V minibox                            |
| C34  | 100/200V                       | 100uF 200V                                      |
| C35  | 100/200V                       | 100uF  200V                                     |
| C36  | 4.7nF                          | 4700pf 250V minibox                             |
| C37  | 0.47uF/250V X2                 | 0.47uF  250V X2 minibox                         |
| C38  | 100/200V                       | 100uF 200V                                      |
| C39  | 100/200V                       | 100uF  200V                                     |
| C40  | 33pf 1kV                       |                                                 |
| C41  | 0.1uF 100V film                |                                                 |
| C42  | 470/10V                        | 470uF 10V                                       |
| C43  | 0.01uF 400V  film              |                                                 |
| C44  | 0.01uF 1kV ceramic disk        |                                                 |
| C45  | 470/10V                        | 470uF  10V                                      |
| C46  | 0.1uF                          | 0.1uF ceramic axial                             |
| CR1  | MR824                          | GI854/MR824                                     |
| CR2  | 1N4150                         |                                                 |
| CR3  | 1N4150                         |                                                 |
| CR4  | 1N4150                         |                                                 |
| CR5  | MR824                          | GI854/MR824                                     |
| CR6  | 1N4150                         |                                                 |
| CR7  | 1N4150                         |                                                 |
| CR8  | 1N4001                         |                                                 |
| CR9  | 1N4007                         |                                                 |
| CR10 | 1N4937                         |                                                 |
| CR11 | RGP02                          | RGP02-12                                        |
| CR12 | 1N4150                         |                                                 |
| CR13 | 1N4150                         |                                                 |
| CR14 | 1N4150                         |                                                 |
| CR15 | 1N5234B                        |                                                 |
| CR16 | 1N4001                         |                                                 |
| CR17 | 1N5234B                        |                                                 |
| CR18 | 1N5234B                        |                                                 |
| CR19 | 1N4001                         |                                                 |
| CR20 | MBR1045                        | MBR1035 / MBR1045                               |
| CR21 | MBR1045                        | MBR1035  / MBR1045 / MBR360                     |
| CR22 | 1N4007                         |                                                 |
| CR23 | 1N4007                         |                                                 |
| CR24 | 1N4007                         |                                                 |
| CR25 | 1N4007                         |                                                 |
| CR26 | 1N4934                         |                                                 |
| CR27 | 1N4001                         |                                                 |
| CR28 | 1N4937                         |                                                 |
| CR29 | 1N4937                         |                                                 |
| CR30 | 1N4007                         |                                                 |
| CR31 | 1N4007                         |                                                 |
| F1   | 1.6A T                         |                                                 |
| J1   | 15-31-1046                     |                                                 |
| J2   | 26-60-4090                     |                                                 |
| J3   | Speaker                        |                                                 |
| J4   | 26-60-4110                     |                                                 |
| J5   | 250V C14 socket                |                                                 |
| L1   | 27uH coil                      |                                                 |
| L2   | 10-50uH  variable coil         |                                                 |
| L3   | Linerarity coil (Apple custom) |                                                 |
| L4   | 27uH axial                     |                                                 |
| L5   | 27uH axial                     |                                                 |
| L6   | 27uH coil                      |                                                 |
| L7   | ??                             |                                                 |
| L8   | 27uH coil                      |                                                 |
| L9   | 27uH coil                      |                                                 |
| L10  | 27uH coil                      |                                                 |
| LF1  | Linefilter                     |                                                 |
| LF2  | Linefilter                     |                                                 |
| NE1  | NE-2H NEON                     |                                                 |
| NE2  | NE-2H NEON                     |                                                 |
| Q1   | NSDU01                         |                                                 |
| Q2   | BU406                          |                                                 |
| Q3   | 2N4401                         |                                                 |
| Q4   | NSDU51                         |                                                 |
| Q5   | 2N5485                         |                                                 |
| Q6   | 2N4401                         |                                                 |
| Q7   | 2N3904                         |                                                 |
| Q8   | 2N6394                         | 2N6394  / 2N6395                                |
| Q9   | 2N3906                         |                                                 |
| Q10  | C3152                          | 2SC  3152                                       |
| Q11  | 2N3906                         |                                                 |
| Q12  | CR400Y                         | CR400Y  / BR103 reversed                        |
| R1   | 220                            | 1/4W                                            |
| R2   | 1.5                            | 1/4W                                            |
| R3   | 1.5                            | 1/4W                                            |
| R4   | 100                            | 1/4W                                            |
| R5   | 470K                           | 1/4W                                            |
| R6   | 4.7K                           | 1/4W                                            |
| R7   | 100                            | 1/4W                                            |
| R8   | 10K                            | 1/4W                                            |
| R9   | 1.5                            | 1/4W                                            |
| R10  | 39/5W                          | 5W  Cement                                      |
| R11  | 100                            | 1/4W                                            |
| R12  | 1M                             | 1/2W                                            |
| R13  | 100K                           | 1/2W                                            |
| R14  | 1K                             | 1/4W                                            |
| R15  | 346K                           | 1% 1/4W                                         |
| R16  | 470                            | 1/4W                                            |
| R17  | 10K                            | 1/4W                                            |
| R18  | 100                            | 1/4W                                            |
| R19  | 100K                           | 1/2W                                            |
| R20  | 100K                           | 1/2W                                            |
| R21  | 1M                             | 1/2W                                            |
| R22  | 100K                           | 1/2W                                            |
| R23  | 470K                           | 1/4W                                            |
| R24  | 220                            | 1/4W                                            |
| R25  | 10K                            | 1/4W                                            |
| R26  | 1M                             | 1/4W                                            |
| R27  | 10K                            | 1/4W                                            |
| R28  | 4.7K                           | 1/4W                                            |
| R29  | 470                            | 1/4W                                            |
| R30  | 470                            | 1/4W                                            |
| R31  | 1K/2W                          | 2W metaloxide                                   |
| R32  | 220                            | 1/4W                                            |
| R33  | 1K                             | 1/4W                                            |
| R34  | 1K                             | 1/4W                                            |
| R35  | 1K                             | 1% 1/4W                                         |
| R36  | 16 4A-ICL  thermistor NTC      |                                                 |
| R37  | 390                            | 1/4W                                            |
| R38  | 10K                            | 1/4W                                            |
| R39  | 1.2K                           | 1% 1/4W                                         |
| R40  | 47                             | 1/4W                                            |
| R41  | 100                            | 1/4W                                            |
| R42  | 1K                             | 1/4W                                            |
| R43  | 100K                           | 1/2W                                            |
| R44  | 100K                           | 1/2W                                            |
| R45  | 390                            | 1/4W                                            |
| R46  | 4.7                            | 1/4W                                            |
| R47  | 1K                             | 1/4W                                            |
| R48  | 39/2W                          | 1W  metaloxide                                  |
| R49  | 1.5                            | 1/4W                                            |
| R50  | 2.2K                           | 1/4W                                            |
| R51  | 220                            | 1/4W                                            |
| R52  | 1K/5W                          | Cement                                          |
| R53  | 1.2                            | 1/4W                                            |
| R54  | 15                             | 1/4W                                            |
| R55  | 33K                            | 1/2W                                            |
| R56  | 2M                             | PT15LV17-200                                    |
| R57  | 2M                             | PT15LV17-200                                    |
| R58  | 500K                           | Potentio                                        |
| R59  | 500                            | Potentio                                        |
| R60  | 1M                             | Potentio                                        |
| R61  | 470K                           | 1/2W                                            |
| R62  | 100                            | 1/4W                                            |
| SW1  | CUSTOM                         | https://github.com/daanvdl/mac_plus_sw1         |
| T1   | Apple custom Flyback           |                                                 |
| T2   | Apple custom transformer       |                                                 |
| T3   | 820-0107-D                     |                                                 |
| U1   | LM324                          |                                                 |
| U2   | LS38                           |                                                 |
| U3   | 4N35                           | 4N35 or CNY17                                   |
| W1   | 0                              | Jumperwire                                      |
| W2   | 0                              | Jumperwire                                      |
| W3   | 0                              | Jumperwire                                      |
| W4   | 0                              | Jumperwire                                      |
| W5   | 0                              | Jumperwire                                      |
| W6   | 0                              | Jumperwire                                      |
| W7   | 0                              | Jumperwire                                      |
| W8   | 0                              | Jumperwire                                      |
| W9   | 0                              | Jumperwire                                      |
| W10  | 0                              | Jumperwire                                      |
| W11  | 0                              | Jumperwire                                      |
| W12  |                                | NOT PLACED ON 220V BOARDS                       |
| W13  | 0                              | Jumperwire                                      |

## Troubleshooting

### Power schematic

See Schematic/PowerCircuit.pdf

The provided power-schematic is a drawing of this specific board *(820-0107-D INTERNATIONAL)*. In the early years Apple did develop multiple versions of the Macintosh analogboard along the line. For both US and internation models there where multiple board versions around and do differ from each other. US & INTERNATIONAL boards have similar video  sections (there's no difference in the adjustment procedure), but the  International version has a completely different power supply.

*Note: If you want to use this schematic to troubleshoot your existing (non-)functioning board, make sure your existing board revision is matching!

### Resources

Reliable resources are:

* **Macintosh Repair & Upgrade Secrets** by Larry Pina
* **The Dead Mac Scrolls** by Larry Pina

Please be aware that you keep in mind that these books are mainly referencing to US board parts. 

### Cross reference

This is a quick cross reference table between the US and INTERNATION boards:

| ID   | US         | INTERNATIONAL |
| ---- | ---------- | ------------- |
| T3   | 157-0047-A | 157-0047-A    |
| CR18 | 1N5927     | 1N5234B       |
|      | R16        | R20           |
|      | R9         | R12           |
|      | R54        | R58           |
|      | R52        | R55           |
|      | R46-R51    | R48-R55       |
|      | R56        | R59           |
|      | Q9-Q10     | Q11-Q12       |
|      | Q11        | Q10           |
|      | Q3         | Q2            |
|      | Q2         | Q4            |

### Usual suspects

| Symptom                         | Possible Solution                                            |
| ------------------------------- | ------------------------------------------------------------ |
| Vertical line                   | Resolder C1,J1,L2<br />Replace C1<br />Replace LAG on logicboard |
| Jitters and/or has worms        | Replace T1                                                   |
| Makes a ringing noise           | Replace T1                                                   |
| Distorts severely/fades/darkens | Replace Q2 (Q3 on US boards), <br />Replace T1               |
| Makes a burning smell/smokes    | Inspect / replace C1,J1,L2 <br/ >Replace Q2 (Q3 on US boards), <br />Replace T1 |
| No raster, completely dark      | Resolder pins 1 and 3 on J4. <br />Replace U2. <br />Replace LAG on logicboard |
| Horizontal line                 | Resolder pin 5 on J4. <br />Suspect Q1 and Q4 (Q4 is Q2 on US boards). <br />Suspect R2 and R3 |
| Pinprick                        | Reconnect CRT yoke cable                                     |
| Dead set (video area OK)        | Test Q10 (Q11 on US boards). Test R52 (R55 on US boards). <br />Test Q8, CR21. <br />Test SQ1, line cord, AC outlet. |
| Dead set (video area burned)    | Replace C1, T1<br />Inspect/replace J1,L2<br />Replace Q2 (Q3 on US boards)<br />Test R48-R55 (R46-R51 on US boards)<br />Test Q11&Q12 (Q9&Q10 on US boards) |
| Flupping set (logicboard OK)    | Check analog to logicboard cable connection<br />Check fuse in line of pin 6 of the logicboard cable <br />Check R59 (R56 on US boards) for +5V<br />Inspect/replace C3,C24,C27-C28,C30-C32 (C3,C24-C26,C29-C31 on US boards)<br />Test/replace CR1,CR5,CR20,CR21<br />Test Q8, 2N6394 crowbar SCR |
| Flupping set (analogboard OK)   | Check analog to logicboard cable connection<br />Check fuse in line of pin 6 of the logicboard cable<br />Replcae TSM chip on logicboard<br />Test 7908 regulator on logic board |

## License

The provided logicboard files are licensed under CC-BY-NC-SA - they are NOT intended for commercial use.

## Disclaimer

This project involves potentially lethal High-Voltage. Construction and operation of this circuit should only be performed by people familiar with best practices when operating with high voltage, and using extreme caution.
I will not be held liable for injury or even death resulting from this part. Build and use this part only at your own risk.