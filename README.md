# M451 Talkback Module · Monitoring

Ward-Beck Systems M451, 1976|9. Wiki page: [M451 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M451.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 42 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 35 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 10 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 240 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 4 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 15 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 57 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [12 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1977 - M451 - Talkback Module.pdf](MANUALS/1977%20-%20M451%20-%20Talkback%20Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Transducer gain** | 88 dB +1 dB |
| **Frequency response** | :1 dB from 100 Hz to 10 kHz |
| **Noise** | -122 dBm Ein _ (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.5% Thd from 100 Hz to 10 kHz at compression threshold and +18 dBm output. |
| **Source impedance** | 150 ohm. |
| **Input impedance** | 750 ohm, baLanced |
| **Input level** | -70 dBm nomina], 30 dBm maximum |
| **Output impedance** | 150 ohm, ba anced |
| **Load impedance** | 600 ohm, balanced |
| **Output level** | +8 dBm nominal, +22 dBm maximum. |
| **Compression ratio** | 5:1, |
| **Compression ratio** | 30 dB |
| **Attack time** | millisecond. |
| **Release time** | second |
| **Phasing** | Input and output termina ] s designated by numbers are in phase |
| **Power requirements** | +25 volts dc, 35 MA |
| **Ambient temperature** | 0 to 60 degrees Celsius 1 6 &quot; wide X 7&quot; high X 6.5 &quot; deep (41 TT X 178 MM X 165 mm) |

## Circuit description

From [1978 - M451 - Talkback Module.pdf](MANUALS/1978%20-%20M451%20-%20Talkback%20Module.pdf) pages 3-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

3 Parts List 3-1 t o 3-5

4 Drawings

1'1451 Front Panel A451 -D 4 -0D 4 1'14 51 Functional B45 1 -01 -00 1 1'1451 sc heee t tc 845 1-02-00 1 1'14 51 Co.po ne n t Layout 8 451 -04 -00 1 1'1 45 1 Connector Layout A451-04-00 2

**WARRANTY**

All Ward -Beck. S y s t~m s Ltd. products are wilr ranted against defective eater l al sand work. man ship fora per10d of one year from date o f shipment.

WardBeck Sy s tells will repair o r replace. a tits option. without char g~. all said products o r parts thereof which. upon factory inspection. prove to bede f e c t t ve during the warranty period provided that:

a) Original serial numbers are intact and have not been tampered with.

b) The purchaser shall return any equipment o r par l s thereof to Ward-Be ck Systems only after obtaining prior e e t no rt aa t t cn and shipping t ns t r uc ti o ns from the factory. Ward-Be Ck Systems reserves the right t o i fl spec tor repair on the purchaser's premises.

c) The purchaser assumes the o b l i ga t ion of 1111 expenses incurred in connection with shipping and returning such goods. once authorization has been obtained.

This warrllnty does not cover items normally cens tde red expendables uc has fuses a fl d h llps.

This warranty does not cover damages caused by misuse, a c ci de flt. neglect. unauthorized alteration. rep.ir by unauthorized personnel. o r dam age caused by act Of God. war o r civil insurrection.

I n no event shall War d-Be ck Systems be liable for consequential damages. Ward-Be ck Systems Shall have the right off ina lee t ere tnat ten as to the applicability of this warranty.

War d-Be c k Systems reserves the right. at anytime. to... ke changes in e qu tp een t, component spec t t t ce t tcns and design as maybe wolrrant~d by progress int e c hno l ogy.

The warranty set forth herein Is in lieu o fall other wa r

ranti es. express o rIm plied. including the warranties of

Mer ch afltolb11lty and Fi ene s s.

**&quot;451 TAL KBACK AMPLIFIER**

Transducer Gain: B8 dB t 1 dB.

Frequency Response::1: 1 dB fro _ 100 Hz t o 10 kHz. Ho ise: -122 d8_ EIN. (20 Hz t o 20 kHz). Ha r_onic Distortion: Less than 0.51 THD from 100 Hz t o 10 kHz at to_p r es sio n threshold and qB dB. output.

se vr-ce I_ped ante: 150 ohm.

Input t spec e nce: 750 ohm, balanced. Input Level:

Outpll t I _pedance: 150 oh., balanced. Load I_pedante: 600 oh., ba 1 an ced. Output tevet:

Co_pr ess ion Ratio: 5: 1.

C o ~ press ion Range: 30 se.

Attack Time: 1 millisecond. Release Time: 1 second.

Phasing: Input and output terminals designated by numbers are i n phase.

Power Requirements::t 25 '0'01 t sec, 35 mA. Ambient Temperature: o t o 60 degrees Celsius. Oi mens1on$: 1.6 &quot; wIde X 7&quot; high X 6.5 &quot; deep. (41 mm X 178 mm X 165 mill).

1• 1

The M451 TA LKBAC K Module is designed to accept inputs from two separate microphone sources. The signal is amplified t o an output level of +8 dBm. Additionally, the unit incorporates a mute control for each input channel, a compressor and a 25 Hz slating oscillator. The output signal can be routed to fours eparat e destinations byway of a pus h-bu tton selector assembly. Preampl i fie rs The first pream plif i e r consists of Tl, 01 and 02, while T2, 04 and 05 maKeup these cond pre amp.

Muting Switches 03 and 06 are functioning as solids tate muting switches, permitting the choice of either pr eampl i fi er output for further processing. The switches are normally in the muted position and maybe switched ON by placing aground potential Onto pins E o r 5 respectively. This control maybe extended from the module t o are mote location such as a prod ucer' s station adjacent t o the console.

Compressor The outputs of the two preampli fi ers are fed t o amplifier Zl via summing resistors R1 6 and R32.07, thea t t e nua tio n element of the compressors ect ion, is placed i n parallel tot he input of Zl. The amplified output of Zl Is coupled through C21 tot he front panel LEVEL control R4 5 as well as tot he THRESHOLD control R44. The signal taken from the wiper of R44 is amplified by Z3 and subsequently rectified by CR1. After filtering, the de voltage, developed in this manner, i s used t o control 07. C17 in conjunction.with R33, R36 and R42 determine there lease character i s tics oft he compressor. R42 sets the bias or opera ting point of 07 and consequently the compression slo ~ characteristics.

Output Amplifier

The audio signal taken from the wiper of R45 is brought t o Z2,010 and 01 1, thus forming one half of the actively balanced

output amplifier. Z2, OB and 09 form the second half of the

output amplifier. The output is brought t o pins 9/ K.

M45l TALK BACK MODULE

25 Hz Osc il h tor A 25 Hz r e l a xat ion oscillator is made up of Z3. C2 2. R53, R54 and R55. A portion of the oscillator signal is injected into Z2 via R49.

The 25 Hz signal appears at the output of the amplifier at a level approximately 20 dB below the nominal output level of +8 dBm.

A normally closed contact of SW5 shorts out the timing capacitor C22 to inhibit the oscillator.

Output Switches The Direct audio output, at pins 9/K. i s normally jump ere d t o pins lOlL t o incorporate selective output routing. SWl to SW4 allow the signal to be routed t o four separate locations. Additionally, each switch i s equipped with a control contact to a common control bus.

SWl is normally employed for slating ina n audio console system. With a jumper wire between pins M and ~, the oscillator will only be activated when both SW land SW5 are depressed. Power Supply Decoupling R7l, R72, C25 and C26 serve to deco uple the M451 from the main power rails. CRl and CR2 prevent damage t o the module int he event of accidental polarity reversal.

WA~O -BECK SYSTEMS L.TC.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0pDX1V5NFByQ3M/view?resourcekey=0-DnEOh_Gln5gM_v8VwXw1qQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0pDX1V5NFByQ3M&resourcekey=0-DnEOh_Gln5gM_v8VwXw1qQ" width="240" alt="1977 - M451 - Slate and M452 Oscillator.jpg"></a><br><sub>1977|10 · Slate and M452 Oscillator</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1977|10 · wbsps - module - m451 slate and m452 oscillator_small](https://drive.google.com/file/d/0B0yR0b5T78SKOFM1RVh1U0hsaDg/view?resourcekey=0-n05fbepeuOX59XYMPWG19g)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKREoyaFI3SDBWRGs/view?resourcekey=0-lYOuhAI7K_c5Pu8AJGd0Cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKREoyaFI3SDBWRGs&resourcekey=0-lYOuhAI7K_c5Pu8AJGd0Cg" width="240" alt="1977 - M451 - 451-04-001 - WAAD-BECK BYBTEMB DRNRMUEIS ENG.jpg"></a><br><sub>1977|10 · 451-04-001 - WAAD-BECK BYBTEMB DRNRMUEIS ENG · <a href="MECHANICAL/1977%20-%20M451%20-%20451-04-001%20-%20WAAD-BECK%20BYBTEMB%20DRNRMUEIS%20ENG%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWll1STRkem5ZZEE/view?resourcekey=0-OnuQ4ffFip60i5Quk5hfoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWll1STRkem5ZZEE&resourcekey=0-OnuQ4ffFip60i5Quk5hfoQ" width="240" alt="1977 - M451 - 451-04-001.jpg"></a><br><sub>1977|10 · 451-04-001 · <a href="MECHANICAL/1977%20-%20M451%20-%20451-04-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMUZVUVcyNjBTNms/view?resourcekey=0-zUcmFNqWfDKK-p8HUo3sdg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMUZVUVcyNjBTNms&resourcekey=0-zUcmFNqWfDKK-p8HUo3sdg" width="240" alt="1977 - M451 - P13 - Front Panel.jpg"></a><br><sub>1977|10 · P13 - Front Panel · <a href="MECHANICAL/1977%20-%20M451%20-%20P13%20-%20Front%20Panel%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1urwba6jnUp8INap5BSVOME4jbBn0A5bj/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1urwba6jnUp8INap5BSVOME4jbBn0A5bj" width="240" alt="19xx - M451 - DOC - 451-03-011 - BEYER TRANSFORMER.jpg"></a><br><sub>19xx - M451 - DOC - 451-03-011 - BEYER TRANSFORMER · <a href="MECHANICAL/19xx%20-%20M451%20-%20DOC%20-%20451-03-011%20-%20BEYER%20TRANSFORMER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1iTXqCh9ykPfM-1I7E2DWjxtLcB_I-01p/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1iTXqCh9ykPfM-1I7E2DWjxtLcB_I-01p" width="240" alt="19xx - M451 - DOC - RAS MOUNTING BRACKET.png"></a><br><sub>19xx - M451 - DOC - RAS MOUNTING BRACKET · <a href="MECHANICAL/19xx%20-%20M451%20-%20DOC%20-%20RAS%20MOUNTING%20BRACKET%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M451.stl`](MECHANICAL/M451.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M451)

- **Size:** 56.57 × 210.72 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 9 holes and cut-outs, 3 knobs (front panel: `MECHANICAL/M451 - front panel.svg`)
- the drawn panel is 0.21 wide to high, the size 0.27: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M451.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUnY3dUdFYXBzd2M/view?resourcekey=0-lC4n-O-eTuD-3ELek3IDKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUnY3dUdFYXBzd2M&resourcekey=0-lC4n-O-eTuD-3ELek3IDKQ" width="240" alt="1977 - M451 - 451-01-001 - FUNCTIONAL DIAGRAM MEA-DJ.jpg"></a><br><sub>1977|10 · 451-01-001 - FUNCTIONAL DIAGRAM MEA-DJ · <a href="SCHEMATICS/1977%20-%20M451%20-%20451-01-001%20-%20FUNCTIONAL%20DIAGRAM%20MEA-DJ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWI1YW90U0g3Q28/view?resourcekey=0-Jq97OgybSMPpXIpSxyQdXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWI1YW90U0g3Q28&resourcekey=0-Jq97OgybSMPpXIpSxyQdXw" width="240" alt="1977 - M451 - 451-02-001 - MOD ICKD USED.jpg"></a><br><sub>1977|10 · 451-02-001 - MOD ICKD USED · <a href="SCHEMATICS/1977%20-%20M451%20-%20451-02-001%20-%20MOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdU4xb3BYdnpQS2c/view?resourcekey=0-M_u5ea7r8snRzbuIB-DChw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdU4xb3BYdnpQS2c&resourcekey=0-M_u5ea7r8snRzbuIB-DChw" width="240" alt="1977 - M451 - 451-02-001 - TALKBACK MODULE SCHEMATIC.jpg"></a><br><sub>1977|10 · 451-02-001 - TALKBACK MODULE SCHEMATIC · <a href="SCHEMATICS/1977%20-%20M451%20-%20451-02-001%20-%20TALKBACK%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/14YqAMmWY67ClNiUGVpqIYMz3p16r2tE6/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=14YqAMmWY67ClNiUGVpqIYMz3p16r2tE6" width="240" alt="1992 - M451 - DOC - 920063-01-002 - PQWER DISIEIBUTIQN PSI.jpg"></a><br><sub>1992|25 · DOC - 920063-01-002 - PQWER DISIEIBUTIQN PSI · <a href="SCHEMATICS/1992%20-%20M451%20-%20DOC%20-%20920063-01-002%20-%20PQWER%20DISIEIBUTIQN%20PSI%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1nJeQ_Iu1uv8ogrX0tFetqlUTM2GrXESA/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1nJeQ_Iu1uv8ogrX0tFetqlUTM2GrXESA" width="240" alt="1992 - M451 - DOC - 920383-01-001 - MONITOR MQDULE SWTCHEO DIRECT FUTURE MONITOR OUTPUTS.jpg"></a><br><sub>1992|25 · DOC - 920383-01-001 - MONITOR MQDULE SWTCHEO DIRECT FUTURE MONITOR OUTPUTS · <a href="SCHEMATICS/1992%20-%20M451%20-%20DOC%20-%20920383-01-001%20-%20MONITOR%20MQDULE%20SWTCHEO%20DIRECT%20FUTURE%20MONITOR%20OUTPUTS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/18ZIdsfxbvvDyfiD84MlNDV3km1vg2hR2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=18ZIdsfxbvvDyfiD84MlNDV3km1vg2hR2" width="240" alt="19xx - M451 - DOC - 600-02-008 - TALKBACK SCHEMATIC.png"></a><br><sub>19xx - M451 - DOC - 600-02-008 - TALKBACK SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M451%20-%20DOC%20-%20600-02-008%20-%20TALKBACK%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVy1WRUZSSWJmNXc/view?resourcekey=0-rK7HA26p2OUUnOPNVJHCoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVy1WRUZSSWJmNXc&resourcekey=0-rK7HA26p2OUUnOPNVJHCoQ" width="240" alt="1977 - M451 - P17 - Pin Outs.jpg"></a><br><sub>1977|10 · P17 - Pin Outs · <a href="PINOUTS/1977%20-%20M451%20-%20P17%20-%20Pin%20Outs%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 7 of 9 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P1-18: kept OUT 4 (out); RTO-144 sheet says GND (ground)
- disagree P1-Y: kept N/C (nc); RTO-144 sheet says VCC-LOGIC (power)

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | OPERATOR MIC | in | OPERATOR MIC | medium |
| 2 | GND | ground |  | medium |
| 3 | PRODUCER MIC | in | PRODUCER MIC | medium |
| 4 | N/C | nc |  | medium |
| 5 | MUTE CTL | control_out | MUTE CTL | medium |
| 6 | N/C | nc |  | medium |
| 7 | N/C | nc |  | medium |
| 8 | N/C | nc |  | medium |
| 9 | OUTPUT | out | OUTPUT | medium |
| 10 | SWITCH IN | in | SWITCH IN | medium |
| 11 | CTL COM | ground |  | medium |
| 12 | AUX | other | AUX | medium |
| 13 | CTL 2 | control_in | CTL 2 | medium |
| 14 | OUT 1 | out | OUT 1 | medium |
| 15 | OUT 2 | out | OUT 2 | medium |
| 16 | CTL 4 | control_in | CTL 4 | medium |
| 17 | OUT 3 | out | OUT 3 | medium |
| 18 | OUT 4 | out | OUT 4 | medium |
| 19 | -25 V | power |  | medium |
| 20 | 25V COM | ground |  | medium |
| 21 | +25 V | power |  | medium |
| 22 | CHASSIS | ground |  | medium |
| A | OPERATOR MIC | in | OPERATOR MIC | medium |
| B | GND | ground |  | medium |
| C | PRODUCER MIC | in | PRODUCER MIC | medium |
| D | N/C | nc |  | medium |
| E | MUTE CTL | control_out | MUTE CTL | medium |
| F | N/C | nc |  | medium |
| H | N/C | nc |  | medium |
| J | N/C | nc |  | medium |
| K | OUTPUT | out | OUTPUT | medium |
| L | SWITCH IN | in | SWITCH IN | medium |
| M | OSC CTL | control_in | OSC CTL | medium |
| N | AUX | other | AUX | medium |
| P | CTL 1 | control_in | CTL 1 | medium |
| R | OUT 1 | out | OUT 1 | medium |
| S | OUT 2 | out | OUT 2 | medium |
| T | CTL 3 | control_in | CTL 3 | medium |
| U | OUT 3 | out | OUT 3 | medium |
| V | OUT 4 | out | OUT 4 | medium |
| W | N/C | nc |  | medium |
| X | N/C | nc |  | medium |
| Y | N/C | nc |  | medium |
| Z | N/C | nc |  | medium |

**Straps:** JMP.Z.W: P2-Z P2-W · JMP.X.18: P2-X P2-18 · JMP.Y.21: P2-Y P2-21 · JMP.3: P2-20 P2-18 · JMP.22.21: P2-22 P2-21 · JMP.Z.Y: P2-Z P2-Y · JMP.20.19: P2-20 P2-19 · JMP.X.W: P2-X P2-W

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkdRV0RvX1lmU3M/view?resourcekey=0-YFBcvgy7LAw5Q97lsxHf5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkdRV0RvX1lmU3M&resourcekey=0-YFBcvgy7LAw5Q97lsxHf5w" width="240" alt="1977 - M451 - P01 - Cover.jpg"></a><br><sub>1977|10 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaDR3SXVGMWxnOUU/view?resourcekey=0-z-kuCjMtvzCpwfDbObYrFg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaDR3SXVGMWxnOUU&resourcekey=0-z-kuCjMtvzCpwfDbObYrFg" width="240" alt="1977 - M451 - P02.jpg"></a><br><sub>1977|10 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTnNzNXhDY2IzVGM/view?resourcekey=0-hF0qm3FHvrKRyQMxPoZwqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTnNzNXhDY2IzVGM&resourcekey=0-hF0qm3FHvrKRyQMxPoZwqw" width="240" alt="1977 - M451 - P04 - Warranty.jpg"></a><br><sub>1977|10 · P04 - Warranty</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSFloTG9RcU9UdUE/view?resourcekey=0-CblWqDmiikCD6NBVK6mlrw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSFloTG9RcU9UdUE&resourcekey=0-CblWqDmiikCD6NBVK6mlrw" width="240" alt="1977 - M451 - P05 - 1-1.jpg"></a><br><sub>1977|10 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0NLbzJJMm4tZDg/view?resourcekey=0-hNznHgfj7ofup1wWiZ0jrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0NLbzJJMm4tZDg&resourcekey=0-hNznHgfj7ofup1wWiZ0jrA" width="240" alt="1977 - M451 - P06 - 2-1.jpg"></a><br><sub>1977|10 · P06 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN093TDFMRGY1MFE/view?resourcekey=0-1axqqLPQDxrbSemebDrwuA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN093TDFMRGY1MFE&resourcekey=0-1axqqLPQDxrbSemebDrwuA" width="240" alt="1977 - M451 - P07 - 2-2.jpg"></a><br><sub>1977|10 · P07 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdDR4UnJ6WGYyVmM/view?resourcekey=0-r1AfbMrG-4it6txPG3vHtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdDR4UnJ6WGYyVmM&resourcekey=0-r1AfbMrG-4it6txPG3vHtA" width="240" alt="1977 - M451 - P08 - 3-1.jpg"></a><br><sub>1977|10 · P08 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2pYaTdaT043TFE/view?resourcekey=0-GXfC4MmuFdEZ_1v6AqoCCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2pYaTdaT043TFE&resourcekey=0-GXfC4MmuFdEZ_1v6AqoCCw" width="240" alt="1977 - M451 - P09 - 3-2.jpg"></a><br><sub>1977|10 · P09 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTmFpay13c3pVOGs/view?resourcekey=0-O2DUYFAsuUtcCnPwQTZ1GA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTmFpay13c3pVOGs&resourcekey=0-O2DUYFAsuUtcCnPwQTZ1GA" width="240" alt="1977 - M451 - P1.jpg"></a><br><sub>1977|10 · P1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGRDZFNnd0tPOVk/view?resourcekey=0-kBSkIYj3tX1BY8Xjmo-wAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGRDZFNnd0tPOVk&resourcekey=0-kBSkIYj3tX1BY8Xjmo-wAw" width="240" alt="1977 - M451 - P10 - 3-3.jpg"></a><br><sub>1977|10 · P10 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKODFaajB5enRwRjQ/view?resourcekey=0-mQa2LAMQqSbxyYTVmGrFUQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKODFaajB5enRwRjQ&resourcekey=0-mQa2LAMQqSbxyYTVmGrFUQ" width="240" alt="1977 - M451 - P10.jpg"></a><br><sub>1977|10 · P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY1pESEY2NWVzSDQ/view?resourcekey=0-wuf38JnMxMrtufkRua49nA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY1pESEY2NWVzSDQ&resourcekey=0-wuf38JnMxMrtufkRua49nA" width="240" alt="1977 - M451 - P11 - 3-4.jpg"></a><br><sub>1977|10 · P11 - 3-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb05ZYkhPLVN2MFE/view?resourcekey=0-MQVYnM5inMUuTo4ysv7xDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb05ZYkhPLVN2MFE&resourcekey=0-MQVYnM5inMUuTo4ysv7xDA" width="240" alt="1977 - M451 - P11.jpg"></a><br><sub>1977|10 · P11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGdsakVLV3dqdzA/view?resourcekey=0-xGlghHXE0NhpfuG7kh-PiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGdsakVLV3dqdzA&resourcekey=0-xGlghHXE0NhpfuG7kh-PiQ" width="240" alt="1977 - M451 - P12 - 3-5.jpg"></a><br><sub>1977|10 · P12 - 3-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSnVnWGJiUkxBVU0/view?resourcekey=0-CbcfIJvPlJi3xTvWXEHPyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSnVnWGJiUkxBVU0&resourcekey=0-CbcfIJvPlJi3xTvWXEHPyw" width="240" alt="1977 - M451 - P12.jpg"></a><br><sub>1977|10 · P12</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdGRIYmdpWVFydkE/view?resourcekey=0-BWS9NeRi959ceXyqJ9nG6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdGRIYmdpWVFydkE&resourcekey=0-BWS9NeRi959ceXyqJ9nG6w" width="240" alt="1977 - M451 - P3.jpg"></a><br><sub>1977|10 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUJ0RnFmZ3l5WGM/view?resourcekey=0-F3Oyj3jymyLzb3E6_knbHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUJ0RnFmZ3l5WGM&resourcekey=0-F3Oyj3jymyLzb3E6_knbHQ" width="240" alt="1977 - M451 - P4.jpg"></a><br><sub>1977|10 · P4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRW5NYkJmTWRmUms/view?resourcekey=0-UDKe5SxKCb0Km4R4R9Zt-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRW5NYkJmTWRmUms&resourcekey=0-UDKe5SxKCb0Km4R4R9Zt-g" width="240" alt="1977 - M451 - P5.jpg"></a><br><sub>1977|10 · P5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkE0N1Y3dEg2aTg/view?resourcekey=0-gchpT9AwUvTrTXKhw02iEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkE0N1Y3dEg2aTg&resourcekey=0-gchpT9AwUvTrTXKhw02iEQ" width="240" alt="1977 - M451 - P6.jpg"></a><br><sub>1977|10 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbU5ZblVrZENMRXM/view?resourcekey=0-kg1SBmxIjhxsfy8FzvxyOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbU5ZblVrZENMRXM&resourcekey=0-kg1SBmxIjhxsfy8FzvxyOQ" width="240" alt="1977 - M451 - P7.jpg"></a><br><sub>1977|10 · P7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNm9FUmdYVWVXVTA/view?resourcekey=0-NlOfHZiTbam9u3bvLqYYAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNm9FUmdYVWVXVTA&resourcekey=0-NlOfHZiTbam9u3bvLqYYAw" width="240" alt="1977 - M451 - P8.jpg"></a><br><sub>1977|10 · P8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNHBfTHZSZzJscmc/view?resourcekey=0-2zjmkuFArV7SzMlYj_dtsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNHBfTHZSZzJscmc&resourcekey=0-2zjmkuFArV7SzMlYj_dtsQ" width="240" alt="1977 - M451 - P9.jpg"></a><br><sub>1977|10 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZXFVSWlHRk9UOGc/view?resourcekey=0-QBKvnA9YTgjIpFe0BGHHJQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZXFVSWlHRk9UOGc&resourcekey=0-QBKvnA9YTgjIpFe0BGHHJQ" width="240" alt="1977 - M451 - Talkback Module (2).pdf"></a><br><sub>1977|10 · Talkback Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3RiOFNsYnRiQW8/view?resourcekey=0-e-hG83d0NLs5O8WEJDQRXA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3RiOFNsYnRiQW8&resourcekey=0-e-hG83d0NLs5O8WEJDQRXA" width="240" alt="1977 - M451 - Talkback Module.pdf"></a><br><sub>1977|10 · Talkback Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclBaQ1RTcDM2MU0/view?resourcekey=0-DgeBTJ2l3oWlOpUCZV6EVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclBaQ1RTcDM2MU0&resourcekey=0-DgeBTJ2l3oWlOpUCZV6EVw" width="240" alt="1978 - M451 - P03 - TOC.jpg"></a><br><sub>1978|11 · P03 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1d6Z2R0VV9xY2s/view?resourcekey=0-XLKHmkj26CUxzoExYX8QSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1d6Z2R0VV9xY2s&resourcekey=0-XLKHmkj26CUxzoExYX8QSw" width="240" alt="1978 - M451 - P2.jpg"></a><br><sub>1978|11 · P2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0k2VzRXdUtqRkE/view?resourcekey=0-jcEpP3Wx0HZG49F0MrK6Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0k2VzRXdUtqRkE&resourcekey=0-jcEpP3Wx0HZG49F0MrK6Lw" width="240" alt="1978 - M451 - Talkback Module (2).pdf"></a><br><sub>1978|11 · Talkback Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQjNkU3Q2R2IxTVU/view?resourcekey=0-2dp-v3vQPd16mhyqipJFCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQjNkU3Q2R2IxTVU&resourcekey=0-2dp-v3vQPd16mhyqipJFCw" width="240" alt="1978 - M451 - Talkback Module.pdf"></a><br><sub>1978|11 · Talkback Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1I9lRAj6XxlnLgAq29r-o81hOi7Ej1v1k/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1I9lRAj6XxlnLgAq29r-o81hOi7Ej1v1k" width="240" alt="19xx - M451 - DOC - 2021-3-16-22-34-19.jpg"></a><br><sub>19xx - M451 - DOC - 2021-3-16-22-34-19</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkhXLWEwUTljVXM/view?resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkhXLWEwUTljVXM&resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" width="240" alt="19xx - M451 - DOC - L2042 - P04.jpg"></a><br><sub>19xx - M451 - DOC - L2042 - P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1RnVXFCRU9UeDA/view?resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1RnVXFCRU9UeDA&resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" width="240" alt="19xx - M451 - DOC - L3242 - P04.jpg"></a><br><sub>19xx - M451 - DOC - L3242 - P04</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanl3MTYxc3RrNkk/view?resourcekey=0-DrZcVip3bpiAYX6ImkrLuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanl3MTYxc3RrNkk&resourcekey=0-DrZcVip3bpiAYX6ImkrLuQ" width="240" alt="19xx - M451 - DOC - L3242 - P10.jpg"></a><br><sub>19xx - M451 - DOC - L3242 - P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0xZZHRMbk1leTA/view?resourcekey=0-ymqmq1Jc4Aq_tFbY9wU8Jw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0xZZHRMbk1leTA&resourcekey=0-ymqmq1Jc4Aq_tFbY9wU8Jw" width="240" alt="19xx - M451 - DOC - P1010006_80 copy.jpg"></a><br><sub>19xx - M451 - DOC - P1010006_80 copy</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M451 - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M451 - DOC - R1400-R2400 - 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSl92a2Vxa2NMc2s/view?resourcekey=0-2dfokMOlctdKaW5lsZMp_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSl92a2Vxa2NMc2s&resourcekey=0-2dfokMOlctdKaW5lsZMp_g" width="240" alt="19xx - M451 - DOC - R1400-R2400 - 014.jpg"></a><br><sub>19xx - M451 - DOC - R1400-R2400 - 014</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1977 - 451-01-001 - TALKBACK MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG RKB - ISS 3 (2).kicad_sch](KICAD/1977%20-%20451-01-001%20-%20TALKBACK%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20RKB%20-%20ISS%203%20(2).kicad_sch)
- [1977 - 451-01-001 - TALKBACK MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG RKB - ISS 3.kicad_sch](KICAD/1977%20-%20451-01-001%20-%20TALKBACK%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20RKB%20-%20ISS%203.kicad_sch)
- [1977 - M451 - 451-01-001 - FUNCTIONAL DIAGRAM MEA-DJ.kicad_sch](KICAD/1977%20-%20M451%20-%20451-01-001%20-%20FUNCTIONAL%20DIAGRAM%20MEA-DJ.kicad_sch)
- [1977 - M451 - 451-01-001 - REVISED DESIGNATIONS REDRAWN REVISION.kicad_sch](KICAD/1977%20-%20M451%20-%20451-01-001%20-%20REVISED%20DESIGNATIONS%20REDRAWN%20REVISION.kicad_sch)
- [1977 - M451 - 451-02-001 - MOD ICKD USED.kicad_sch](KICAD/1977%20-%20M451%20-%20451-02-001%20-%20MOD%20ICKD%20USED.kicad_sch)
- [1977 - M451 - 451-02-001 - TALKBACK MODULE SCHEMATIC.kicad_sch](KICAD/1977%20-%20M451%20-%20451-02-001%20-%20TALKBACK%20MODULE%20SCHEMATIC.kicad_sch)
- [1977 - M451 - Talkback Module (2) p14.kicad_sch](KICAD/1977%20-%20M451%20-%20Talkback%20Module%20(2)%20p14.kicad_sch)
- [1977 - M451 - Talkback Module p14.kicad_sch](KICAD/1977%20-%20M451%20-%20Talkback%20Module%20p14.kicad_sch)
- [1977 - M451 - Talkback Module p15.kicad_sch](KICAD/1977%20-%20M451%20-%20Talkback%20Module%20p15.kicad_sch)
- [1986 - B --02-006 - INPUT MODULE SCHEMATIC - DRN GEB.kicad_sch](KICAD/1986%20-%20B%20--02-006%20-%20INPUT%20MODULE%20SCHEMATIC%20-%20DRN%20GEB.kicad_sch)
- [1992 - M451 - DOC - 920063-01-002 - PQWER DISIEIBUTIQN PSI.kicad_sch](KICAD/1992%20-%20M451%20-%20DOC%20-%20920063-01-002%20-%20PQWER%20DISIEIBUTIQN%20PSI.kicad_sch)
- [1992 - M451 - DOC - 920383-01-001 - MONITOR MQDULE SWTCHEO DIRECT FUTURE MONITOR OUTPUTS.kicad_sch](KICAD/1992%20-%20M451%20-%20DOC%20-%20920383-01-001%20-%20MONITOR%20MQDULE%20SWTCHEO%20DIRECT%20FUTURE%20MONITOR%20OUTPUTS.kicad_sch)
- [19xx - M451 - DOC - 600-02-008 - TALKBACK SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M451%20-%20DOC%20-%20600-02-008%20-%20TALKBACK%20SCHEMATIC.kicad_sch)
- [M451 - P14 - Functional Diagram.kicad_sch](KICAD/M451%20-%20P14%20-%20Functional%20Diagram.kicad_sch)
- [M451.kicad_sym](KICAD/M451.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
