---
layout: page
title: Eye In The Sky
permalink: /eits
---

## An augmented-reality heads-up-display system for enhanced situational awareness in aviation
![](/assets/system.png){:class="img-responsive"}

Eye in the Sky was created to alleviate visibility difficulties in small-scale aviation, where existing systems such as TCAS may prove prohibilitively expensive to equip.
The system uses an integrated Septentrio Mosaic-X5 GPS module and RTL-SDR software defined radio to obtain the positions of the user and nearby aircraft, then calculates positions of nearby aircraft relative to the user. This is then projected onto the image plane of an attached MIPI CSI camera to provide a front-facing stream of the aircraft with annotations of any potential surrounding collision hazards.


Features:
- Custom minimal linux distribution "Skynix"
- Data aggregation and decoding from aircraft transponders via ADS-B on 1090MHz through RTL-SDR software-defined radio
- Computation of relative positions and distances from user to surrounding aircraft
- Camera stream and raw data display to framebuffer of attached display
- Spatial annotation of aircraft in image plane (WIP)
- Active hazard warning system according to FAA Minimum Safe Distance regulations (WIP)
- Trajectory prediction and guidance (planned)


The codebase and documentation for the device service may be obtained from the [eye-in-the-sky GitHub repository](https://github.com/jklingspon/eye-in-the-sky/).
SolidWorks part files for the enclosure are hosted on the [eits-cad repository](https://github.com/jklingspon/eits-cad).
