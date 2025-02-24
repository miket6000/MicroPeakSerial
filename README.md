# MicroPeakSerial

The MicroPeakSerial is heavily based off the design detailed here [MicroPeakSerial](https://keithp.com/blogs/MicroPeakSerial/) by Keith Packard, but in KiCad rather than geda and including a housing designed in FreeCAD.

The only real changes are to include a USB A connector instead of the micro B to remove the need for a cable and to the footprint. A USB C connector was considered, but my prefered field laptop is old enough to not have one!

It should be noted that the current housing appears to hold the MicroPeak too far above the photo transistor for it to work effectively. I'm unsure at this point if I'll adjust the housing, or make improvements to the MicroPeakSerial by AC coupling the signal and using some positive feedback in the opamp to implement a basic bistable schmidt trigger. The latter option seems the better solution but brings a little complexity in ensuring the bistable opamp always powers up in the correct state.

TBC...
