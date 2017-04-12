# kicad_microbit_connector

## A KiCad component library and footprint library for micro:bit edge connector

This is a schematic & PCB-layout library, for use with [KiCad](http://kicad-pcb.org/), an open source PCB design/layout tool.

The [micro:bit](http://microbit.org/) has an 80 pin edge connector (not all pins are active), at 0.05" / 1.27mm pitch.  Sockets for the edge conector are easy to obtain (right-angle) and harder to obtain (straight).

This library was written for the through-hole, straight version of the socket.  It has had limited testing, but is in successful use for PCB manufacture.

#### Contents

- [lib_microbit_connector](./lib_microbit_connector) - schematic
- [lib_microbit_connector.pretty](./lib_microbit_connector.pretty) - footprint


#### TODO

- a right-angle version of the footprint (PR welcome)
- 3D-model visual to go with the footprint

