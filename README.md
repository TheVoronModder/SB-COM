![Voron](https://img.shields.io/badge/Voron-Compatible-red)
![Toolhead](https://img.shields.io/badge/Toolhead-StealthBurner-black)
![Belts](https://img.shields.io/badge/Belts-9mm-green)
![Belts](https://img.shields.io/badge/Belts-6mm-green)
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



-------------------------------------------------------------------------------------------------


<img width="5000" height="1543" alt="Save The StealthBurner" src="https://github.com/user-attachments/assets/9c4654dc-24c3-4824-9c3b-07462d038b1f" />

# Save the StealthBurner

> Improving the StealthBurner toolhead through better COM, smarter design, and real-world data.

---

## Introduction

**Save the StealthBurner.**

So what’s going on here?

The StealthBurner toolhead gets a bad rap — and honestly, in stock form, some of that is fair.  
But it’s also the toolhead that got me into building a Voron in the first place.

So instead of ditching it…  
**we fix it.**

---

## Current Roadmap

- Rapido 2 UHF integration
- Thunderkeys FilamATrix support

---

## 2026 (→ 2027) Roadmap

### Hotend / Filament Cutter Support

- CHC-XL  
- Rapido 2 UHF  
- Thunderkeys FilamATrix  

---

## COM Calibration Method

Before we dive in:

Fusion 360 calculates **solid mass (no air)**.  
3D printed parts are not solid — even at 100% infill — so calculated weights are inaccurate.

To fix this:

- Printed a real part  
- Measured actual weight  
- Back-calculated density for accurate COM simulation  

---

### Print Settings Used

- 4 walls  
- 4 top / bottom layers  
- 40% rectilinear infill  
- 0.4 mm nozzle  
- Ambrosia ASA  

<img width="3000" height="700" alt="COM Weight Issues" src="https://github.com/user-attachments/assets/ddc78743-416e-417e-9333-a8aa3d476adc" />

---

## Important Component Weights

| Component | Weight |
|----------|--------|
| ECAS fitting | 1 g |
| Cartographer v3 | 4 g |
| 4010 Winsinn fan | 11 g |
| Standard 4010 fan | 13 g |
| Rapido 2 UHF | 47 g |
| LDO-36STH20-1004AHG | 85 g |

---

## SB-COM

**StealthBurner — optimized for center of mass**

---

### MGN12 Printed Carriage  
#### (Monolith 9mm Belt Compatible)

<img width="3000" height="1004" alt="9mm SB MGN12 Carriage" src="https://github.com/user-attachments/assets/aa2d6445-0bf2-4028-8113-7183827e065e" />

This carriage is not expected to have perfect COM — but it's a major improvement.

Key change:
- Replaced heat inserts with **304 stainless square nuts**
- Cleaner load path + better serviceability

---

### Update — CW2 Assembly Added

⚠️ Motor weight not finalized yet  
(Need to measure actual LDO stepper before updating COM model)

<img width="3000" height="1004" alt="9mm SB CW2" src="https://github.com/user-attachments/assets/690e45c6-8b80-4033-9ae8-84f2ba03427d" />

---

![SB ALL TOGETHER](https://github.com/user-attachments/assets/8697b763-df04-4c43-b086-2a0f6f73c4d3)




