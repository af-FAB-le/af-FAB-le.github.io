---
title: "[Capush] pan-tilt camera unit"
date: 2022-04-03T16:44:53+02:03
draft: false
images: 
- "/images/pan-tilt-cam.jpg"
---

The pan-tilt camera is an extension of the [fixed camera](/capush/fixed-cam/). It is also installed permanently in the environment but its camera is mounted on a pan-tilt assembly enabling rotations around the pan and tilt axis for more control over the focus area. The control of the pan-tilt assembly can be automatic or manual. The latter lets makers control the orientation of the camera either through physical manipulations or through a (virtual) joystick interface displayed on a computer or smartphone's screen.
Automatic control permits to track a specific tool or object while performing an activity, that is, objects of interest can remain in focus even if the makers move them. This approach is especially useful to capture a process including the displacement of pieces and tools on a workbench.

### Bill of material
- 1 Raspberry Pi (we used a Pi3B+ but a smaller form factor such as a Pi Zero W should be sufficient)
- 1 Raspberry Camera Module V2
- Pan/tilt frame with 2 SG90 servos 
- PCA9685 Servo Shield