# Summary-of-SPT-4-Cryostat-Design

## My Engineering Analyses:
- [Optics tube design](https://github.com/ahryciuk/SPT-4-Optics-Tube-Design/tree/main)
- [Vacuum window modeling and prototyping](https://github.com/ahryciuk/SPT-4-Vacuum-Window-Prototype)
- [Thermal gradient analysis](https://github.com/ahryciuk/Thermal-Gradient-Analysis-of-SPT-4-Cryostat)
- [Modal analysis of support structures](https://github.com/ahryciuk/Modal-Analysis-of-SPT-4-Cryostat-Support-Structures)
- [Thermal budgeting for selection of cryogenics](https://github.com/ahryciuk/Thermal-Budgeting-of-SPT-4-Cryostat)
  

## Overview of Instrument:

The SPT-4 (SPT-3G+) Cryostat is a 100 milliKelvin millimeter-wave receiver to be deployed in the Austral summer of 2028-2029. The focal plane is made up of ~34,000 microwave kinetic inductance detectors (MKIDs). I led the integrated design of this instrument, performed engineering analyses to verify design choices, and built a prototype of the vacuum window subassembly. The resultant design is the main subject of my thesis. Below are some summary figures and links to my various analyses.

SPT-4 Cryostat (quarter cutaway):
<p align="center">
  <img src="final_CAD_renders./SemiTransparentWindow_SPT4ProposalFigure.JPG" width="600">
</p>

There are seven individual optics tubes with bandpasses centered at 220 GHz, 280 GHz, and 345 GHz. The tubes are mounted to the 4 Kelvin subassembly so the silicon lenses are cold. I developed custom torsional-spring mounts to provide precision alignment of the lenses and to counteract their cracking due to thermal stress.
<p align="center">
  <img src="final_CAD_renders./SPT4_optics_tube_cutaway.PNG" width="600">
</p>

The sensitive cryogenic environment is maintained by a Bluefors SD250 Dilution refrigerator and a Cryomech PT420 Pulse Tube cryo-cooler. The internals of the cryostat are contained within a set of three nested cylinders heat sunk to progressively lower temperatures (300 Kelvin, 50 Kelvin, and 4 Kelvin). This nested design dramatically limits the radiative heat transfer to the focal plane, allowing the dilution refrigerator to maintain the 100 milliKelvin temperature for the MKID detectors. 
<p align="center">
  <img src="final_CAD_renders./SPT4_exploded_view.PNG" width="600">
</p>

Annotated half-cutaway:
<p align="center">
  <img src="final_CAD_renders./SPT4_cutaway_annotated.PNG" width="600">
</p>

