---
title: "[Capush] fixed camera unit"
date: 2022-04-04T16:44:53+02:10
draft: false
images: 
- "/images/fixed-cam.jpg"
---

The fixed cam is a basic unit type whose main functionality is to provide access to a networked camera. For our proof of concept implementation, we selected a Raspberry PI as the base unit as it has a small form factor while providing the convenience of a full Linux distribution. These boards come equipped with a range of wired and wireless network connections, and are often readily available in many fabrication workshops. Our fixed camera unit uses a [Raspberry Camera Module V2](https://www.raspberrypi.org/documentation/hardware/camera/). We opted for the use of Raspberry camera modules as they provide a good trade-off between image quality and size. The standard V2 module provides a 8-megapixel camera and is capable of recording 1080p/30 video. Many other variants exist including ones featuring 12-megapixel, auto focus, fish-eye lenses or night vision. As the name suggests, a fixed camera unit is meant to be installed permanently, thus it uses a regular external power supply.

### Bill of material
- 1 Raspberry Pi (we used a Pi3B+ but especially for a fixed camera unit, which has no particular computation need, a smaller form factor such as a Pi Zero W should be sufficient)
- 1 Raspberry Camera Module V2
- A case to hold the two items together and facilitate attaching the unit somewhere. For example, this [3D printed case by barneyj on thingiverse](https://www.thingiverse.com/thing:256960).