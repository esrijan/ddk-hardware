ddk-hardware
============

Device Development Kit (DDK)'s hardware design & development project.

DDK is a brain child of Anil Kumar Pugalia <anil_pugalia@eSrijan.com>. It
started as a hobby of designing electronics circuit PCBs, as part of the
Computer Club of India (http://computerclub.in). And now, it is complete
Electronics Device (AVR uC) Development (EDDK) & Linux Device Drivers
(learning) (LDDK) kit(s).

This project is released under the Juice Sharing License (See LICENSE file
for details). Files under libs: Few have been created and others have been
obtained from various freely available sources.

It has been designed using kicad. And this directory contains the
corresponding kicad files, along with the following in capital letters:

+ README.md - this file
+ LICENSE - project's license file

+ libs - additional libraries used apart from the default kicad installation
+ ddk.pro - kicad project file
+ ddk.net - netlist file
+ ddk.sch - schematic (eeschema) file
+ ddk.cmp - component mapping (cvpcb) file. Also, updated from pcbnew.
+ ddk.brd - board layout (pcbnew) file
+ ddk-Front* - front component layer output files (using pcbnew plot)
+ ddk-Back* - back copper layer output files (using pcbnew plot)
+ ddk-Mask* - mask output files (using pcbnew plot)
+ ddk-SilkS* - silk screen output files (using pcbnew plot)
+ ddk-drl.* - drill size output files (using pcbnew plot)

+ ddk.pdf - schematic explicitly generated in .ps (-> .pdf) using eeschema plot
+ ddk.lst - components list explicitly generated using eeschema
+ ddk.stf - component detailing explicitly generated using cvpcb for
	back-annotating into eeschema
+ ddk.drl - drill file explicitly generated using pcbnew plot
+ ddk.csv - BOM explicitly generated using pcbnew
+ ddk.bom - updated BOM from soldering requirement angle (not yet updated for DDK v2.0)
