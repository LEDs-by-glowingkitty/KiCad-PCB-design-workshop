# KiCad-PCB-design-workshop
This repo contains most of the files related to my [PCB design workshop using KiCad 7](https://workshops.glowingkitty.com). To learn how you can build a simple PCB and then continue with easily building a more complex LED project.

## This workshop is made possible by your donation

Donations are split between xHain (the non-profit space where we meet, for providing the space) and me (for the time and effort I put into the workshop). If you want to say thank you and support the workshops, I suggest a donation of 10€-30€.

[Donate via PayPal](https://paypal.glowingkitty.com/)

[Donate via Apple Pay / Google Pay / Card](https://revolut.glowingkitty.com/)

If this is currently financially difficult for you: telling others about [my workshops](https://workshops.glowingkitty.com) also helps me out a lot. 

Thank you!

## Workshop preparation

### Download KiCad 7

To download KiCad 7 (Release Candidate), check out their downloads page (currently in the nightly builds section):

[MacOS (1.4GB)](https://downloads.kicad.org/kicad/macos/explore/nightlies)

[Windows (1.2GB, the latest .exe)](https://downloads.kicad.org/kicad/windows/explore/nightlies)

[Linux (Nightly Development Builds)](https://www.kicad.org/download/)

## Start KiCad and make sure you have the libraries installed

Start KiCad, setup the recommended default settings, then go to Preferences -> Manage Symbol Libraries and make sure you have a bunch of libraries installed, similar to this:

![screenshot](/readme%20images/kicadsymbols.jpeg)

If the list is empty instead, you can download the libraries from the following links and add them manually. If you have difficulties with that, we can do it together during the workshop.

[Download symbols (8.1MB)](https://gitlab.com/kicad/libraries/kicad-symbols/-/archive/7.0.0-rc2/kicad-symbols-7.0.0-rc2.zip)

[Download footprints (43.3MB)](https://gitlab.com/kicad/libraries/kicad-footprints/-/archive/7.0.0-rc2/kicad-footprints-7.0.0-rc2.zip)

**(Optional for workshop, but recommended for every day use):**

[Download the 3D models (955.6MB)](https://gitlab.com/kicad/libraries/kicad-packages3D/-/archive/7.0.0-rc2/kicad-packages3D-7.0.0-rc2.zip)

## After the workshop, feel free to check out these resources for KiCad

### My KiCad parts library

[Download my parts library (plus datasheets, around 700MB)](https://codeload.github.com/glowingkitty/KiCad-parts-library/zip/refs/heads/main)

### Plugins

**kicad-jlcpcb-tools**

Plugin to generate BOM + CPL files for JLCPCB, assign LCSC part numbers directly from the plugin, query the JLCPCB parts database, lookup datasheets and much more.

https://github.com/Bouni/kicad-jlcpcb-tools


**JLC2KiCad_lib**

JLC2KICAD_lib is a python script that generates a component library (schematic, footprint and 3D model ) for KiCad from the JLCPCB/easyEDA library.

https://github.com/TousstNicolas/JLC2KiCad_lib


## If you want to order your PCBs (with or without components)

**JLCPCB (China)**

https://jlcpcb.com

**PCBway (China)**

https://pcbway.com

**Aisler (Germany)**

https://aisler.net


## Components for your PCBs, if you want to assemble the PCBs yourself

**LCSC (China)**

https://lcsc.com

**DigiKey (USA)**

https://digikey.com

**Mouser (USA)**

https://mouser.com