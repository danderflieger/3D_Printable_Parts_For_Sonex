# Aveo PowerBurst NG Daylight Wing-end Light Mounts

This project contains 3D printable parts designed in Solid Edge that allow you to connect the Aveo PowerBurst NG Daylight wing end position/strobe lights to a Sonex wingend. The Sonex wingend rib is set at 45° and the lights needs a 45° offset mount for the lights to point directly outward (as opposed to 45° downward).

There are two ways to make the light mounts:
- you can 3D print the mount and use it straight off the 3D printer
- you can 3D print a 2-piece mold and lay up either fiberglass or carbon fiber with a 2-part resin. 

In either case, I have included the .par (Solid Edge part) and STL files in this repository. 


## 3D printed part
  Location: Aveo PowerBurst NG Daylight Mount/3D Printable

In the case of direcly using a printed part, be sure to print it in a material that can withstand the elements. PLA is plant based and will deteriorate outdoors. Additionally, it's not very heat resistant, so the part is likely to reach its "glassing" temerature on a hot summer day. When a 3D printable filament reaches its glassing temperature, wil begins to become soft and will no longer hold its shape. I suggest ABS or ASA filament for this project. Even better, a carbon fiber (CF) infused ABS or ASA filament. The CF particles do not grow/shrink with temperature change and your part is more likely to hold its shape.

I have added STL files for these 3D models: __Aveo PowerBurst NG Daylight Mount/3D Printable/STL Files/__


## 3D printed mold for compsite lay-up
  Location: Aveo PowerBurst NG Daylight Mount/Composite Molds

I have prepared a second option for those interested in laying up a composite material. I changed the part to have a slight "draft" (a bevel that allows the part to be easily removed from a mold). This option has three Solid Edge part files:

- __Aveo PowerBurst NG Daylite Mount-With-Draft.par__ - this file is the new part with the draft. The dimmensions are the same as the 3D printable part on the side where the light is affixed. However, with the draft, the side that butts up against the wingend rib is slightly larger as it follows the draft. This part can be printed and used to make a mold out of composites material (or printed and used as-is, like the option above). 
- __Aveo PowerBurst NG Daylite Mount-Mold-Cavity.par__ - This is the concave portion of the mold that can be 3D printed.
- __Aveo PowerBurst NG Daylite Mount-Mold-Core.par__ - This is the convex portion of the mold that can be 3D printed.

I have added STL files for these 3D models: __Aveo PowerBurst NG Daylight Mount/Composite Molds/STL Files__

Note: I used Solid Edge to determine that the volume of the drafted part is  31.343 cm^3. I suggest using:
- 21.2 grams of carbon fiber
- 14.2 grams of resin

I came to these values by watching [this video](https://www.youtube.com/watch?v=nhqAhYOdGNc&t=12m24s). I suggest watching the entire video - it's very enlightening. 

Here are my calculations base on the numbers provided in the video:
23.572 cm^3 (part volume) x 1.5 grams of carbon fiber + resin (by weight) per cm^3 = 35.358 grams of carbon fiber + resin
Of that total, we want to use 60% carbon fiber (by weight) and 40% resin (by weight). So ...
- 35.358 grams x 60% = 21.2148 grams of carbon fiber (rounded to 21.2 grams)
- 35.358 grams x 40% = 14.1432 grams of resin (rounded to 14.2 grams)


OLD VALUES - Before updated model with more draft an thinner walls:

<del>31.434 cm^3 (part volume) x 1.4 grams of carbon fiber and resin per cm^3 of volume = 44.0076 grams of carbon fiber + resin
Of that total, we want to use 60% carbon fiber (by weight) and 40% resin (by weight). So ... </del>
- <del>44.0076 grams x 60% (0.60) = 26.40456 grams of carbon fiber (rounded to 26.4 grams)</del>
- <del>44.0076 grams x 40% (0.40) = 17.60304 grams of resin (rounded to 17.6 grams)</del>

## 3D Print Settings
I elected to print my parts using PETG-CF filament, .2mm layers, 3mm walls, 3mm top/bottom, with 50% infill. I over-estimated the amount of strength needed for all of the printed parts. On my upgraded Creality Ender3 printer, the Cavity took 11 hours to print and the Core took about 13 hours. Remember that you will also need to print both of those parts mirrored to make the mount for the left wing. I didn't model a separate part, just mirror the STL files in your slicing software before printing them. 
