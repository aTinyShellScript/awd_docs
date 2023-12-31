---
hide:
  - navigation
---
# A Voron v2.4 AWD Mod

<div class="video-wrapper">
  <iframe width="640" height="360" src="https://www.youtube-nocookie.com/embed/Lp676hJnY2M?start=8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Getting Started

So you're thinking about burning some money? 

Decide what size steppers you want to use (NEMA14 recommended) and select [Metal](/metal_parts) or [Printed](/printed_parts) from the menu up top.

![Gantry](images/Gantry.png)

Visualization of space lost with NEMA14s with Xol toolhead on a 350mm bed.

![Bed Space Loss](images/nema14_xol_350bed.png)
<sub><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Image Credit: @.skeebo on Armchair Engineering Discord</sub></sup>

### But Why?

* Pros
    * You will be able to (probably) print faster with less vibration.
        * Having two steppers per belt helps equalize the tension on the belt during fast moves.
    * Metal (if you use them) plates help dissipate heat from your steppers, so you can run higher currents.
    * For 2WD, you can get rid of those stupid front tensioners that break.
    * Looks cool. Bling is always a good thing.
    * Works with existing XYjoints.
* Cons
    * If modifying an existing printer (or building from BOM or a Kit) you will lose a small amount of bed space.
        * For NEMA14s, you will lose between 10x10mm and 20x20mm of space, depending on the toolhead you use.
            * For the original NEMA14 plates (and Funssor CNC plates) this is more like 20x20 to 30x30.
        * For NEMA17s, you can expect to lose betweeen 25x25 and 40x40mm of space.
        * For 2WD, you lose no space.
    * Cost and complexity

## Still Have Questions?

You can find discussion about this mod in the [Armchair Engineering Discord](https://discord.gg/armchairengineeringsux). There is a thread in `user-projects`.
