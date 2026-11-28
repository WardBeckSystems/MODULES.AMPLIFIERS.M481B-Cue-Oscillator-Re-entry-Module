# M481B Cue Oscillator Re-entry Module · Amplifiers

Ward-Beck Systems M481B, 1982|15. Wiki page: [M481B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M481B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 28 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 108 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 9 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 26 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [8 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1982 - M481B - Cue OSC Re-entry Module.pdf](MANUALS/1982%20-%20M481B%20-%20Cue%20OSC%20Re-entry%20Module.pdf) page 2 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 25 dB +/-2 dB (bridging gain) |
| **Frequency response** | +/-1 dB from 100 Hz to kHz |
| **Noise** | 80 dB below watts output (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.5% from 100 Hz to kHz at watts output. |
| **Source impedances** |  |
| &nbsp;&nbsp;External cue input | Cue/Solo Input: 600 ohms maximum; balanced 600 ohms maximum, balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;External cue input | Cue/Solo Input: 600 ohms, balanced. 30,000 ohms, balanced, |
| &nbsp;&nbsp;Input level |  |
| **External cue input** | Cue/Solo Input: +8 dBm nominal +24 dBm maximum. 18 dBm nominal +24 dBm maximum. |
| **Output level** | Less than 0.5 ohm. |
| **Load impedance** | 8 ohms, unbalanced |
| **Output impedance** | 200 milliwatts nominal, watts maximum under normal program conditions. M2 Eo MI Rezentry |
| **Nominal level control setting** | dB in hand. |
| **Input level** | +8 dBm nominal, +24 dBm maximum. |

## Circuit description

From [1982 - M481B - Cue OSC Re-entry Module.pdf](MANUALS/1982%20-%20M481B%20-%20Cue%20OSC%20Re-entry%20Module.pdf) pages 5-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The output from the first section of u1 operates into the inverting integrating amplifier formed by the second section of U1 The amplitude of the positive feedback is determined by R34 and the amplitude stabilizing clipping diodes CR3 and CR4. The phase shift determined by the second section of U1; controls the amount of positive feedback and therefore the distortion RB is normally adjusted to give an output with approximately 0.57 distortion at frequency of kHz. RlO i5 the osci Ta or Level trim adjustment, which Ts accessible vTa small hole in the module front panel u2 are output buffer amplifiers which provide an actively balanced output at pins K of the module connector at nominal Level of 48 dBrri - Additionally, there Ts take-otf at Pins 10 L to feed the meler selector. loss network R49 R50 and R9 feeds reference level through switch Swi to Masters and 2. Re-entry The M2 output appearing at pins 17 &amp; U ot this module; is routed through MI Re-en try switch Sw3 and Re-entry Level control RS/R6 to summing resistors R27 and R28 These resistors connect to the M1 summing bus via pins 8 at the module connector AuX Master Level Control The AuX Master level control is connected to the Aux Master insert point of the M4B7 dual master module. Power_Supply Power is derived from the console integral +/ -25 volt supply which appears a[ pins 21 and 19 of the module connector. It is coupled through polarity reversing diodes CRI and CR2 to tne decoupling Timer networks R14, R1S; and C1 through C4. This Ts internally connected Lo tne oscillator and preamplifier section of the cue amplifier at nominal value ot +/ = 16 volts. The watt amplifier U4 derives its power from the 125 volts supply rail via fuse FI and CR6. C19 filters the supply voltage to U4.

PARTS LiST

**MFG PART NUMBER**

C1 C2 c3 C4 C5 Capacitor 22uF /25 Siemens 841313-45226-2 68uF/6 Kemet

**C6 C? CB C9 C10**

S0OpF Aselco ca92-MC-152m 1OuF /25 V Kerrie[

**T390C |06MO25AS**

Cii C12 C13 C14 C15 1OOOpF 6800pF 1OOuF/25 680pF 6800pF Aselco c092-MC-102m c092 MC-682m 426ETF100 2222-630-03681 ca92 MC 682M Philips Aselco C16 C17 C1B C19 C20 CRI CR2 CR3 CRL CRS CR6 470uF /16 V Siemens 1OuF /25 Kemet

**B41283-44477-T 1390C 106MO25A5**

1OOuF /25 V Philips 22uF /25 Siemens

**426ETF100 8413I3-45226-2 IN4003**

Diode, Zener Motorola

**IN4003**

Fuse 0.5A FB Relay Potentiometer Buss Siemens NB

**R7 R8**

Trim Pot 50K 50k Piher PtiOH sok

PARTS LiST

**MFG PART NUMBER**

R9 R10 Ri) Trim Pot 500 Sk 5k 'A' Piher PTIOH 500 PTiOV 5k WBS 10-015 Potentiometer

**R12 R13 R14 R15 R16**

Resistor i/4w5% 620 8K2 750 750 270 Philips RI? R1B R19 R20 270 15k 15k 3k

**R2I R22 R23 R24 R25**

3k 620 15k 15K ak?

**R26 R27 R2B R29 R30**

4k7 15k 15k' 15K 10ok

**R3I R32 R33 R34 R35**

15k 15K 91k 10k 47K

**R36 R37 R38 R39 R40**

10k 620 Ak? 22k 4k7

**R41 R42 R43 R44**

15k 15k 620 15k

PARTS LiST Mh8iB CUE OSCILLATOR RE-ENTRY MODULE

**R45 R46 R4? R48 RL9**

Resistor 1/4w 5% 15k 22k 4K7 4K7 I0k Philips

**RSO R5I R52 R53 R54**

10k 220 2K2 300 300 1/2w 5% 1/4w 596

**R55 R56 R57**

J00 300 620 Swi SW2 SW3 Switch

**WBS 11-002**

U1 u2 u3 44 Integrated circuit National

**RI) R2)**

Knob (Black) Cap (Black) Elma 021-352 040-302

**R3) R4)**

Knob (Black Cap (Black) 021-352 040-302 Rs) R6) Knob (Black) Cap (Black 021-352 040-302

Knob (Black) Cap (Black) 021-352 040-302

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKckRJWHo2cXFmNkk/view?resourcekey=0-2ibxhTRMvIXQSwSI7Yi-EA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKckRJWHo2cXFmNkk&resourcekey=0-2ibxhTRMvIXQSwSI7Yi-EA" width="240" alt="1982 - M481B - 481-04-002 - AUX MASTER REF OSC.jpg"></a><br><sub>1982|15 · 481-04-002 - AUX MASTER REF OSC · <a href="MECHANICAL/1982%20-%20M481B%20-%20481-04-002%20-%20AUX%20MASTER%20REF%20OSC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M481B.stl`](MECHANICAL/M481B.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M481B)

- **Size:** 62.2 × 341.03 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 10 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M481B - front panel.svg`)
- the drawn panel is 0.15 wide to high, the size 0.18: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M481B.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbmlya3JCc1Y4bkE/view?resourcekey=0-heUDHu2F9dyqjgKksnANBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbmlya3JCc1Y4bkE&resourcekey=0-heUDHu2F9dyqjgKksnANBA" width="240" alt="1982 - M481B - 481-02-002 - CUE OSC RE-ENTRY MODULE SCHEMATIC.jpg"></a><br><sub>1982|15 · 481-02-002 - CUE OSC RE-ENTRY MODULE SCHEMATIC · <a href="SCHEMATICS/1982%20-%20M481B%20-%20481-02-002%20-%20CUE%20OSC%20RE-ENTRY%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVnJ2emdGR3F0VkU/view?resourcekey=0-f9DgWlgL--7qVLhxT_CQow" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVnJ2emdGR3F0VkU&resourcekey=0-f9DgWlgL--7qVLhxT_CQow" width="240" alt="1982 - M481B - 481-06-002 - CUE OSC RE-ENTRY MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1982|15 · 481-06-002 - CUE OSC RE-ENTRY MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1982%20-%20M481B%20-%20481-06-002%20-%20CUE%20OSC%20RE-ENTRY%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTFlETE5KXzJEOXc/view?resourcekey=0-DpTIi2ca_9NvmwLc_XHomA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTFlETE5KXzJEOXc&resourcekey=0-DpTIi2ca_9NvmwLc_XHomA" width="240" alt="1982 - M481B - P13 - Functional Diagram.jpg"></a><br><sub>1982|15 · P13 - Functional Diagram · <a href="SCHEMATICS/1982%20-%20M481B%20-%20P13%20-%20Functional%20Diagram%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVV5dmFuelFnVEk/view?resourcekey=0-THUpqiJeQc-SHnp3UY_IeA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVV5dmFuelFnVEk&resourcekey=0-THUpqiJeQc-SHnp3UY_IeA" width="240" alt="19xx - M481B - DOC - 1202-02-011 - REDRAWN FOR.jpg"></a><br><sub>19xx - M481B - DOC - 1202-02-011 - REDRAWN FOR · <a href="SCHEMATICS/19xx%20-%20M481B%20-%20DOC%20-%201202-02-011%20-%20REDRAWN%20FOR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSzVWcnpkTEFZTm8/view?resourcekey=0-FJF7HDRRrq82yig-wShWHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSzVWcnpkTEFZTm8&resourcekey=0-FJF7HDRRrq82yig-wShWHg" width="240" alt="19xx - M481B - DOC - 1202-02-012 - OOP SHE-DS.jpg"></a><br><sub>19xx - M481B - DOC - 1202-02-012 - OOP SHE-DS · <a href="SCHEMATICS/19xx%20-%20M481B%20-%20DOC%20-%201202-02-012%20-%20OOP%20SHE-DS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSW9DVDFJUjhHNDA/view?resourcekey=0-LsRL7zmoNnMRkR9JkF5V2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSW9DVDFJUjhHNDA&resourcekey=0-LsRL7zmoNnMRkR9JkF5V2A" width="240" alt="19xx - M481B - DOC - 1202-02-017 - POSTS CHASSIS GROUND.jpg"></a><br><sub>19xx - M481B - DOC - 1202-02-017 - POSTS CHASSIS GROUND · <a href="SCHEMATICS/19xx%20-%20M481B%20-%20DOC%20-%201202-02-017%20-%20POSTS%20CHASSIS%20GROUND%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## RTO-144 pinout

21 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 8 | RE-ENTRY THE M2 OUTPUT | out |  | medium |
| 11 | RE-ENTRY SELECTOR AND LEVEL CONTROL OF MASTER | control |  | medium |
| 12 | RE-ENTRY SELECTOR AND LEVEL CONTROL OF MASTER | control |  | medium |
| 13 | CUE/SOLO ASSI GN SWITCH SW2 ROUTES THIE | control |  | medium |
| 17 | RE-ENTRY THE M2 OUTPUT | out |  | medium |
| 19 | POWERSUPPLY POWER | power |  | medium |
| 21 | POWERSUPPLY POWER | power |  | medium |
| N | RE-ENTRY SELECTOR AND LEVEL CONTROL OF MASTER | control |  | medium |
| U | RE-ENTRY THE M2 OUTPUT | out |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkhQMS1VamozNE0/view?resourcekey=0-Kn8bAfUeWzOHYXlVq5XIoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkhQMS1VamozNE0&resourcekey=0-Kn8bAfUeWzOHYXlVq5XIoA" width="240" alt="1982 - M481B - Cue OSC Re-entry Module (2).pdf"></a><br><sub>1982|15 · Cue OSC Re-entry Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRE9xUjhqbzJtNWs/view?resourcekey=0-b_2MSSH2kw06Tm4LtbO2WQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRE9xUjhqbzJtNWs&resourcekey=0-b_2MSSH2kw06Tm4LtbO2WQ" width="240" alt="1982 - M481B - Cue OSC Re-entry Module.pdf"></a><br><sub>1982|15 · Cue OSC Re-entry Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRW8tbFFzN0FhVzQ/view?resourcekey=0-BJADUH4DLRZ1VsEPbWtokA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRW8tbFFzN0FhVzQ&resourcekey=0-BJADUH4DLRZ1VsEPbWtokA" width="240" alt="1982 - M481B - P01 - TOC.jpg"></a><br><sub>1982|15 · P01 - TOC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2pqTlFSaUpCOWc/view?resourcekey=0-VHnCy_YCVb4t0-2RnStBbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2pqTlFSaUpCOWc&resourcekey=0-VHnCy_YCVb4t0-2RnStBbQ" width="240" alt="1982 - M481B - P02 - 1-1.jpg"></a><br><sub>1982|15 · P02 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc0kwd2wzeEVQTm8/view?resourcekey=0-UoDiJlRu6oMuGZg8MLQ9rw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc0kwd2wzeEVQTm8&resourcekey=0-UoDiJlRu6oMuGZg8MLQ9rw" width="240" alt="1982 - M481B - P03 - 1-2.jpg"></a><br><sub>1982|15 · P03 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDUtcVhfemVvbVk/view?resourcekey=0-YxDM0RXgwSU0Es7AS_X5aA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDUtcVhfemVvbVk&resourcekey=0-YxDM0RXgwSU0Es7AS_X5aA" width="240" alt="1982 - M481B - P04 - 2-1.jpg"></a><br><sub>1982|15 · P04 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWk10SVdCcldqR2s/view?resourcekey=0-1hGRITb-3mGeErJ1G8tl7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWk10SVdCcldqR2s&resourcekey=0-1hGRITb-3mGeErJ1G8tl7g" width="240" alt="1982 - M481B - P05 - 2-2.jpg"></a><br><sub>1982|15 · P05 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnUtRjNzOVVNblk/view?resourcekey=0-DyG362Lv4KkeQd9p9nYnyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnUtRjNzOVVNblk&resourcekey=0-DyG362Lv4KkeQd9p9nYnyw" width="240" alt="1982 - M481B - P06 - 3-1.jpg"></a><br><sub>1982|15 · P06 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNXV3VEMzZXVQYkk/view?resourcekey=0-338M3KFK__dmbXwufj3YlQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNXV3VEMzZXVQYkk&resourcekey=0-338M3KFK__dmbXwufj3YlQ" width="240" alt="1982 - M481B - P07 - 3-2.jpg"></a><br><sub>1982|15 · P07 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkRFQjQ4Q1hGakU/view?resourcekey=0-P8E1Ss7xwswRil7rOJEdbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkRFQjQ4Q1hGakU&resourcekey=0-P8E1Ss7xwswRil7rOJEdbg" width="240" alt="1982 - M481B - P08 - 3-3.jpg"></a><br><sub>1982|15 · P08 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNVZ6bmxiMl9hNWM/view?resourcekey=0-AE2ExuwMMrQGh624RWGSTw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNVZ6bmxiMl9hNWM&resourcekey=0-AE2ExuwMMrQGh624RWGSTw" width="240" alt="1982 - M481B - P09 - 3-4.jpg"></a><br><sub>1982|15 · P09 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWFHeDI3QkRsczg/view?resourcekey=0-yWRJxekjyh6GqCtpH_0GRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWFHeDI3QkRsczg&resourcekey=0-yWRJxekjyh6GqCtpH_0GRQ" width="240" alt="1982 - M481B - P10 - 4-1.jpg"></a><br><sub>1982|15 · P10 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGVKeFlBTlo1Y2c/view?resourcekey=0-RHBJyIhclMC1LY4818CaBw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGVKeFlBTlo1Y2c&resourcekey=0-RHBJyIhclMC1LY4818CaBw" width="240" alt="1982 - M481B - P11 - 5-1.jpg"></a><br><sub>1982|15 · P11 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMi1rcjZwbXMyOUE/view?resourcekey=0-V82wewC7Mz-xGA5v3tieXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMi1rcjZwbXMyOUE&resourcekey=0-V82wewC7Mz-xGA5v3tieXg" width="240" alt="19xx - M481B - DOC - L1202A - P12 - 1-9.jpg"></a><br><sub>19xx - M481B - DOC - L1202A - P12 - 1-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKem5nZ1pUZkVwNVk/view?resourcekey=0-xjiax86LOvodGR8P0DzKPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKem5nZ1pUZkVwNVk&resourcekey=0-xjiax86LOvodGR8P0DzKPA" width="240" alt="19xx - M481B - DOC - L1202A - P20 - 111-2.jpg"></a><br><sub>19xx - M481B - DOC - L1202A - P20 - 111-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVhfTkl0SlowOEU/view?resourcekey=0-v_4paYZZELRQ2qXyvFBgyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVhfTkl0SlowOEU&resourcekey=0-v_4paYZZELRQ2qXyvFBgyw" width="240" alt="19xx - M481B - DOC - L1202A - P22 - 111-4.jpg"></a><br><sub>19xx - M481B - DOC - L1202A - P22 - 111-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSU1GVElVaEpFRnM/view?resourcekey=0-uDfNpm8pY_aQnjDK71iSbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSU1GVElVaEpFRnM&resourcekey=0-uDfNpm8pY_aQnjDK71iSbg" width="240" alt="19xx - M481B - DOC - L1202A - P23 - 111-5.jpg"></a><br><sub>19xx - M481B - DOC - L1202A - P23 - 111-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGVVUmx1MlN1ek0/view?resourcekey=0-vJM2sfewluMBwXhSfCFOAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGVVUmx1MlN1ek0&resourcekey=0-vJM2sfewluMBwXhSfCFOAg" width="240" alt="19xx - M481B - DOC - L1202A - P25 - IV-1.jpg"></a><br><sub>19xx - M481B - DOC - L1202A - P25 - IV-1</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1982 - M481B - 481-02-002 - CUE OSC RE-ENTRY MODULE SCHEMATIC.kicad_sch](KICAD/1982%20-%20M481B%20-%20481-02-002%20-%20CUE%20OSC%20RE-ENTRY%20MODULE%20SCHEMATIC.kicad_sch)
- [1982 - M481B - Cue OSC Re-entry Module (2) p1.kicad_sch](KICAD/1982%20-%20M481B%20-%20Cue%20OSC%20Re-entry%20Module%20(2)%20p1.kicad_sch)
- [1982 - M481B - Cue OSC Re-entry Module p15.kicad_sch](KICAD/1982%20-%20M481B%20-%20Cue%20OSC%20Re-entry%20Module%20p15.kicad_sch)
- [1982 - M481B - P13 - Functional Diagram.kicad_sch](KICAD/1982%20-%20M481B%20-%20P13%20-%20Functional%20Diagram.kicad_sch)
- [19xx - M481B - DOC - 1202-02-011 - REDRAWN FOR.kicad_sch](KICAD/19xx%20-%20M481B%20-%20DOC%20-%201202-02-011%20-%20REDRAWN%20FOR.kicad_sch)
- [19xx - M481B - DOC - 1202-02-012 - OOP SHE-DS.kicad_sch](KICAD/19xx%20-%20M481B%20-%20DOC%20-%201202-02-012%20-%20OOP%20SHE-DS.kicad_sch)
- [19xx - M481B - DOC - 1202-02-017 - POSTS CHASSIS GROUND.kicad_sch](KICAD/19xx%20-%20M481B%20-%20DOC%20-%201202-02-017%20-%20POSTS%20CHASSIS%20GROUND.kicad_sch)
- [M481B - P13 - Functional Diagram.kicad_sch](KICAD/M481B%20-%20P13%20-%20Functional%20Diagram.kicad_sch)
- [M481B.kicad_sym](KICAD/M481B.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
