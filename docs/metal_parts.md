---
hide:
  - navigation
---
# Metal ABAB Drives

## Non-Metal Parts
Some bits still have to be printed.

* The printed parts are listed in the STL directory of the GitHub repo under either [STL/NEMA14/MetalPlates](https://github.com/aTinyShellScript/v2.4_AWD/tree/main/STLs/NEMA14/MetalPlates) or [STL/NEMA17/MetalPlates](https://github.com/aTinyShellScript/v2.4_AWD/tree/main/STLs/NEMA17/MetalPlates) depending on your stepper size. 
* For 2WD, you do not need the 'FrontMidBody' parts but you need two additional '10mmSpacer'.

## All Wheel Drive
The NEMA14 and NEMA17 versions share the same BOM.

### BOM
    * 16x F695-2RS Bearings
    * 12x F623-2RS Bearings
    * 2x M5x30mm
    * 2x M5 Nuts
    * 6x 20mm M3 Metal Standoffs
    * 12x M3x8mm
    * 16x M3x30mm

### Assembly

Use the CAD for info on how to assemble.

Just make sure you put the correct plate (with M5 and M3 holes for the side extrusion) on the bottom for the rear AB drives, it's important otherwise it won't fit.

## Two Wheel Drive
* Even without adding two extra steppers, you can gain benefits from using metal plates for your AB drives. The increased heatsinking provided will allow you to run higher currents than you could with ABS/ASA parts previously.
  
* There are printable Simple Idlers located in the `Printed` sub-folder if you aren't concerned about chamber temps.

### BOM
    * 16x F695-2RS Bearings
    * 2x M5x30mm
    * 2x M5 Nuts
    * 6x 20mm M3 Metal Standoffs
    * 12x M3x8mm
    * 8x M3x30mm

### Assembly
2WD setups need to keep the stock Voron belt path and not the flipped belt path of the AWD version that is shown in the CAD. See the image below for the correct orientation of the pulleys and tensioner parts.

![2WD Gantry Orientation](images/2wd_gantry.png)

Use the CAD for info on how to assemble.

Just make sure you put the correct plate (with M5 and M3 holes for the side extrusion) on the bottom for the rear AB drives, it's important otherwise it won't fit.