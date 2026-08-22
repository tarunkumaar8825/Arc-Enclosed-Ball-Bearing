[![DOI](https://zenodo.org/badge/1342606895.svg)](https://doi.org/10.5281/zenodo.22057497)

# Arc Enclosed Ball Bearing

## Technical Field
This disclosure relates to mechanical power transmission and rotary bearings. Specifically, it establishes public prior art for a scalable, open-ended, parametric mechanical architecture for an "arc enclosed ball bearing assembly".

## Intent of Publication
This documentation and its accompanying design files are deliberately published as a public disclosure to establish prior art under 35 U.S.C. § 102(a)(1) (and equivalent international patent laws).

## Parametric Architecture & Functional Working Principles
Consists of two raceways, inner and outer. The Outer Raceway is naturally higher diameter with a lower angular displacement, while the Inner raceway has a higher angular displacement and the delta provides the total travel of the bearing.

This structure is fully scalable and modular across each parameter configuration:
- **Variable Angular Extent:** The rolling path is defined by a flexible angular sector length ($x^\circ$) (refer PDF documents). The total travel of the raceway is defined by ($Δ^\circ$) for the inner bearing having an angle ($x+Δ^\circ$).
- **Dimensional Scalability:** Physical scale, raceway slot depth ($y\text{ mm}$), boundary diameters, and ball counts are entirely variable depending on the application *.STEP documents are made for 6mm balls.

To use the given modules, simply change the inner diameter in the Inner Raceway of the first extrude to match the shaft, the outermost diameter in the Outer Raceway to your frame, and scale the dimensions to fit Bearing balls as necessary.

## Repository File Structure
- [`Arc Enclosed Ball Bearing.STEP`](<Arc Enclosed Ball Bearing.STEP>) : 3D geometric reference standard.
- [`Inner Raceway Drawing.PDF`](<Inner Raceway Drawing.PDF>) : 2D schematic illustrating rough geometric layout of inner raceway.
- [`Outer Raceway Drawing.PDF`](<Outer Raceway Drawing.PDF>) : 2D schematic illustrating rough geometric layout of outer raceway.

## Licensing
This hardware design is licensed under the CERN Open Hardware License Version 2 – Permissive (CERN-OHL-P-2.0). You may use, modify, and distribute this design under the terms of the CERN-OHL-P-2.0. You are not required to share derivative designs or modifications. Distributed WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [`CERN-OHL-P-2.0`](<LICENSE>) for more details.
