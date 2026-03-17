![Voron](https://img.shields.io/badge/Voron-Compatible-red)
![Toolhead](https://img.shields.io/badge/Toolhead-StealthBurner-black)
![Belts](https://img.shields.io/badge/Belts-9mm-green)
![Hotend](https://img.shields.io/badge/Hotend-Rapido%202%20UHF-orange)
![Status](https://img.shields.io/badge/Status-Experimental-yellow)

<img width="5000" height="1543" alt="Save The StealthBurner" src="https://github.com/user-attachments/assets/9c4654dc-24c3-4824-9c3b-07462d038b1f" />


# Introduction

Save the StealthBurner!

Whats going on here?

Simply put, I personally feel the StealthBurner toolhead gets a bad rap. It totally does in stock form, so I wanted to save it beacuse its what made me want to build a Voron printer...

# Current roadmap:

* Getting Rapido 2 UHF finalized
* Thunderkeys FilamATrix

--------------------------------------------

# 2026 (closer to 2027) Roadmap:

## Hotend Support / Filament Cutter Support List:

* CHC-XL
* Rapido 2 UHF
* Thunderkeys FilamATrix Support

Before we dive in...

Couple of notes. Fusion 360 uses solid mass, meaning NO AIR, when we 3d print parts sure, air is trapped, and even though we may print at 100% it may never weigh the same as a solid injection mold part, most of these parts are not suitable for injection molding anyway....

So...

I printed 1 part the one below and used its actual weight to determine the correct ratio for fusion to calculate.

Rules are simple:

* 4 Walls
* 4 Solid Top / Bottom layers
* 40% Rectilinear infill
* .4mm nozzle
* Ambrosia ASA
  
<img width="3000" height="700" alt="COM Weight Issues" src="https://github.com/user-attachments/assets/ddc78743-416e-417e-9333-a8aa3d476adc" />

# Important Weights
* ECAS - 1 gram
* Cartographer v3 - 4 grams
* 4010 Winsinn Amazon fan - 11 grams (regular fans without deep set holes for SHCS is 13 grams)
* Rapido 2 UHF - 47 grams
* LDO-36STH20-1004AHG - 85 grams



# SB-COM
StealthBurner but good COM

## MGN12 Printed Carriage for Monolith 9mm Belts

<img width="3000" height="1004" alt="9mm SB MGN12 Carriage" src="https://github.com/user-attachments/assets/aa2d6445-0bf2-4028-8113-7183827e065e" />


I do not expect the Carriage to have a perfect COM, however, its interesting to see where we are at with the added mods eliminating heatserts from the face of the toolhead mount, instead utilizing 304ss square nuts.

## UPDATE, added CW2 Assembly, NOTE- The Motor is not right yet, I need to weight my LDO stepper motor before adding the weight...

<img width="3000" height="1004" alt="9mm SB CW2" src="https://github.com/user-attachments/assets/690e45c6-8b80-4033-9ae8-84f2ba03427d" />


![SB ALL TOGETHER](https://github.com/user-attachments/assets/8697b763-df04-4c43-b086-2a0f6f73c4d3)








<img width="5000" height="1543" alt="Save The StealthBurner" src="https://github.com/user-attachments/assets/9c4654dc-24c3-4824-9c3b-07462d038b1f" />
Save the StealthBurner
Introduction

Save the StealthBurner.

So what's going on here?

Simply put, the StealthBurner toolhead gets a bad rap. In stock form, some of that criticism is deserved. But it's also the toolhead that inspired me to build my first Voron printer, so I wanted to see if it could be improved instead of abandoned.

This project focuses on improving:

Center of Mass (COM)

Hotend compatibility

Toolhead rigidity

Weight distribution

The goal is simple:

Keep the StealthBurner aesthetic and ecosystem — but make it perform better.

Current Roadmap

Finalizing Rapido 2 UHF support

Thunderkeys FilamATrix integration

2026 (Closer to 2027) Roadmap
Hotend / Filament Cutter Support

Planned support includes:

CHC-XL

Rapido 2 UHF

Thunderkeys FilamATrix

COM Calculations

Before diving in, there are a couple of important notes.

Fusion 360 calculates solid mass, meaning no air volume inside the model. When we 3D print parts, however, air is trapped within the infill structure. Even at 100% infill, the printed part may not weigh the same as a solid injection-molded part.

Additionally, many of these parts are not suitable for injection molding anyway, so the mass calculations must be adjusted.

To solve this:

I printed a single reference part, measured its actual weight, and used that data to determine the proper density ratio so Fusion can more accurately calculate COM.

Printing Rules Used for Calibration

All COM calculations are based on the following print configuration:

4 Walls

4 Top / Bottom Layers

40% Rectilinear Infill

0.4 mm Nozzle

Ambrosia ASA

<img width="3000" height="700" alt="COM Weight Issues" src="https://github.com/user-attachments/assets/ddc78743-416e-417e-9333-a8aa3d476adc" />
Important Component Weights

Reference weights used for COM simulation:

ECAS fitting — 1 g

Cartographer v3 probe — 4 g

4010 Winsinn fan (Amazon) — 11 g

Standard fans without deep SHCS mounting holes — 13 g

Rapido 2 UHF hotend — 47 g

LDO-36STH20-1004AHG stepper motor — 85 g

SB-COM

StealthBurner with improved Center of Mass

MGN12 Printed Carriage
Designed for Monolith 9mm Belts
<img width="3000" height="1004" alt="9mm SB MGN12 Carriage" src="https://github.com/user-attachments/assets/aa2d6445-0bf2-4028-8113-7183827e065e" />

I do not expect the carriage to achieve a perfect COM, but it is interesting to see where the design lands after several modifications.

One key change is eliminating heat inserts on the face of the toolhead mount, replacing them with 304 stainless steel square nuts for improved serviceability and strength.

Update

CW2 assembly has been added for further testing.

Note:
The motor weight is currently incorrect in the model. I still need to weigh my actual LDO stepper motor before adding the correct value to the COM calculation.

<img width="3000" height="1004" alt="9mm SB CW2" src="https://github.com/user-attachments/assets/690e45c6-8b80-4033-9ae8-84f2ba03427d" />
