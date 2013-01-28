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
+ usb_driver_kit.pro - kicad project file
+ usb_driver_kit.net - netlist file
+ usb_driver_kit.sch - schematic (eeschema) file
+ usb_driver_kit.cmp - component mapping (cvpcb) file
+ usb_driver_kit.brd - board layout (pcbnew) file
+ usb_driver_kit-Component* - component layer output files
+ usb_driver_kit-Copper* - copper layer output files
+ usb_driver_kit-Mask* - mask output files
+ usb_driver_kit-SilkS* - silk screen output files

+ usb_driver_kit.pdf - schematic explicitly generated in .ps (-> .pdf) using eeschema
+ usb_driver_kit.lst - components list explicitly generated using eeschema
+ usb_driver_kit_soldering.lst - updated components list from soldering requirement angle
+ usb_driver_kit.stf - component detailing explicitly generated using cvpcb for
	back-annotating into eeschema
+ usb_driver_kit.drl - drill file explicitly generated using kicad
