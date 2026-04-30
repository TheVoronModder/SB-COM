![Toolhead](https://img.shields.io/badge/Toolhead-StealthBurner-black)
![Belts](https://img.shields.io/badge/Belts-9mm-green)
![Belts](https://img.shields.io/badge/Belts-6mm-green)
![Hotend](https://img.shields.io/badge/Hotend-Rapido%202%20UHF-orange)
![Status](https://img.shields.io/badge/Status-Experimental-yellow)

-------------------------------------------------------------------------------------------------


<img width="5000" height="1543" alt="Save The StealthBurner" src="https://github.com/user-attachments/assets/9c4654dc-24c3-4824-9c3b-07462d038b1f" />

# Save the StealthBurner

StealthBurner helped shape modern DIY 3D printer toolhead design, and the Voron development team deserves huge credit for the years of work, testing, and community support that made it what it is today.

This project explores what happens when the platform is pushed further using a CPAP-focused cooling approach designed around higher airflow, improved thermal performance, and continued experimentation.

Rather than replacing the original design philosophy, this project builds on it — keeping the core identity of StealthBurner while exploring new ideas in cooling efficiency, airflow behavior, acoustics, and print performance.

At its core, SB-COM is an engineering experiment driven by curiosity, iteration, and community collaboration. Some ideas may work better than others, but that is part of what makes open-source hardware fun.

If you enjoy testing new concepts, tuning hardware, and pushing printer platforms beyond their original limits, you are probably in the right place.

# Our goal is simple:

* Keep the spirit of StealthBurner alive
* Improve cooling performance through CPAP
* Continue experimenting, refining, and sharing results with the community
* Build on the foundation the Voron team created

At this time, this project is CPAP ONLY.
The current focus is centered around high-airflow cooling development, duct refinement, weight balancing, and real-world print performance testing.

We are still actively testing and improving the design. Some areas are complete, while others are still evolving as more data and feedback come in.

Because sometimes the best designs are the ones that continue to evolve.

# Disclaimer: the air ducts are an improvement on the current design, however, there is more work to be done, Its easy to re print hotend mounts and install them so its okay that it will be fine tuned later 😉
---

## Current Roadmap

- Rapido 2 UHF integration
- Thunderkeys FilamATrix support
- Goliath / CHC XL hotend
- Monolith Gantry Support

## Monolith Below
<img width="4016" height="1142" alt="monolith 6mm and 9mm MMU Support Filamatrix" src="https://github.com/user-attachments/assets/7d745766-0f54-464f-94c8-2a5badd90c29" />

## Future Roadmap

- Voron belt path
- Chube Mini

---

# Real World Results: 

Voron Trident 300mm
LDO 2504 Motors 45mm tall shafts
48v

<img width="9000" height="3480" alt="sb-com" src="https://github.com/user-attachments/assets/56f15d12-55f7-4e25-a620-5a29bee63482" />


## COM Calibration Method

Before we dive in:

Fusion 360 calculates **solid mass (no air)**.  
3D printed parts are not solid — even at 100% infill — so calculated weights are inaccurate.

To fix this:

- Printed a real part  
- Measured actual weight  
- Back-calculated density for accurate COM simulation
- New Density = Current Density × (Target Mass ÷ Current Mass)​

## Check out my Fusion 360 Density calculator here: https://thevoronmodder.github.io/SB-COM/

---

### Print Settings Used

- 4 walls  
- 4 top / bottom layers  
- 40% rectilinear infill  
- 0.4 mm nozzle  
- Ambrosia ASA  

<img width="3000" height="700" alt="COM Weight Issues" src="https://github.com/user-attachments/assets/ddc78743-416e-417e-9333-a8aa3d476adc" />

## Image shows the weight variance between CAD and SLICER... The real world weights found below are from using my wifes Sourdough kitchen scale 🤣
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

## Important Printed Part weights:
These are all printed using Ambrosia ASA Filament, please note your filament weights may be slightly different due to filament manufacturing and filament mix, Ambrosia is known to have some PETG very minimal though.

| Component                                   | Weight                                                                 | Notes                          |
|--------------------------------------------|--------------------------------------------------------------------------|----------------------------------|
| Rapdio 2 UHF 6mm Voron Style Back Plate | 26g (printed total weight) - 5 walls, 5 top/bottom 100% rectilinear infill | Reflected in Fusion CAD file |
| CW3 Cover NON MMU | 20g (printed total weight) - 5 walls, 5 top/bottom 20% rectilinear infill | Reflected in Fusion CAD file |
| CW3 Counter Weight | 18g (printed total weight) - 5 walls, 5 top/bottom 100% rectilinear infill | Reflected in Fusion CAD file |


---

# More Updates coming soon!


MANY THANKS:
| Item | Link |
|----------|------------------------|
| Voron Stealthburner | https://github.com/VoronDesign/Voron-Stealthburner|
| FilamATrix |  https://github.com/thunderkeys/FilamATrix/tree/main |

