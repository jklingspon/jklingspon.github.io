---
layout: page
title: Eye In The Sky
permalink: /eits
---

## An augmented-reality heads-up-display system for enhanced situational awareness in aviation
![](/assets/system.png){:class="img-responsive"}

Eye in the Sky was created to alleviate visibility difficulties in small-scale aviation, where existing systems such as TCAS may prove prohibilitively expensive to equip.
The system uses an integrated Septentrio Mosaic-X5 GPS module and RTL-SDR software defined radio to obtain the positions of the user and nearby aircraft, then calculates positions of nearby aircraft relative to the user. This is then projected onto the image plane of an attached MIPI CSI camera to provide a front-facing stream of the aircraft with annotations of any potential surrounding collision hazards.

The related codebase may be obtained from the [eye-in-the-sky github repository](https://github.com/jklingspon/eye-in-the-sky/).
