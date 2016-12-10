# KiCad Third-Part Tools

> A curated list of third-party tools to be used in conjunction with the
[KiCad](http://kicad-pcb.org/) open-source electronics design
automation suite.

*Please read the [contribution guidelines](contributing.md) before contributing.*



## Table of Contents

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Schematic Tools](#schematic-tools)
    - [Schematic Entry Tools](#schematic-entry-tools)
    - [Symbol Library Tools](#symbol-library-tools)
    - [Bill of Materials (BOM) Tools](#bom-tools)
- [PCB Layout Tools](#pcb-layout-tools)
    - [Footprint Library Tools](#footprint-library-tools)
    - [Layout Tools](#layout-tools)
- [Viewer Tools](#viewer-tools)
    - [KiCad Format Viewer Tools](#kicad-format-viewer-tools)
<!-- /TOC -->



## Schematic Tools

### Schematic Entry Tools

- [Skidl](http://xesscorp.github.io/skidl) - A  module that allows you
to compactly describe the interconnection of electronic circuits and components
using Python. The resulting Python program performs electrical rules checking
for common mistakes and outputs a netlist that serves as input to
a PCB layout tool such as KiCad's PCBNEW.

- [KiField](https://xesscorp.github.io/KiField) - A utility for manipulating
part fields in KiCad schematics. KiField can extract all the component fields
from a schematic and place them into a spreadsheet for bulk editing, after
which you can insert the edited values from the spreadsheet back into the schematic.


### Symbol Library Tools

- [Quick Library Generator](http://kicad.rohrbacher.net/quicklib.php) - A web service to generate common "box type" symbols for ICs from pin descriptions. 

- [KiPart](https://xesscorp.github.io/KiPart) - A utility that generates single
and multi-unit symbols from a CSV file containing all the pin information for
one or more parts.

- [KiField](https://xesscorp.github.io/KiField) - A utility for manipulating
part fields in KiCad symbol libraries. KiField can extract all the component fields
from a library and place them into a spreadsheet for bulk editing, after
which you can insert the edited values from the spreadsheet back into the library.


### BOM Tools

- [KiCost](https://xesscorp.github.io/KiCost) - A utility that generates a
spreadsheet from a schematic filled with the part pricing information scraped
from distributors like Digi-Key, Mouser, etc. For each distributor and part,
the spreadsheet contains the quantity-dependent prices, available quantities,
link to the part page, and ordering codes.



## PCB Layout Tools

### Footprint Library Tools

- [monostable/kicad_footprints](https://github.com/monostable/kicad_footprints) - A collection of all the KiCad footprints available on the internet and some scripts to manage them. 

- [svg2mod](https://github.com/mtl/svg2mod) - A tool to convert multi-layer Inkscape SVGs into footprints. 

- [xess_fp_wizard.py](https://github.com/xesscorp/xess_fp_wizard) - A utility
to make footprints for chips having pins around the periphery (SOICs, QFP, etc.)
and ball grid arrays (BGAs).

### Layout Tools

- [Laksen/kicad-bga-tools](https://github.com/Laksen/kicad-bga-tools) - A script to generate via fanouts for BGA components on a board.



## Viewer Tools

### KiCad Format Viewer Tools

- [eyrie.io](http://eyrie.io) - Insight into KiCad EDA designs using a web browser on desktop, laptop, tablet or phone. Browser based schematic and layout viewer that uses WebGL for fast viewing of even complex KiCad designs. Eyrie URLs preview well on Twitter and Facebook and allow deep linking to specific views and design elements. oEmbed support means Eyrie URLs embed well on sites like Wordpress with previews. Eyrie can view KiCad files directly from GitHub, Dropbox or via drag/drop upload to the browser. Google Doc style comments allows for clear discussion about specific aspects of KiCad designs. Octopart integration allows for detailed expression of design intent using real world part specs and datasheets. Free for open source designs and students.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [XESS Corp.](http://xess.com) has waived all copyright and related or neighboring rights to this work.
