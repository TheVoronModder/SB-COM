![Voron](https://img.shields.io/badge/Voron-Compatible-red)
![Toolhead](https://img.shields.io/badge/Toolhead-StealthBurner-black)
![Belts](https://img.shields.io/badge/Belts-9mm-green)
![Belts](https://img.shields.io/badge/Belts-6mm-green)
![Hotend](https://img.shields.io/badge/Hotend-Rapido%202%20UHF-orange)
![Status](https://img.shields.io/badge/Status-Experimental-yellow)

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
