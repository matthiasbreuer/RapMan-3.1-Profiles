# RapMan 3.1 Skeinforge profiles

These are Skeinforge 50 (http://skeinforge.com) profiles for the RapMan 3.1 printer from BitsFromBytes. The settings are mostly copied over from the BitsFromBytes Axon 2 software to pure Skeinforge with some modifications.

## Profile Naming

The profile names are made up of a few different tokens:

* RM3.1 -- Indicates RapMan v3.1
* PLAXX -- Name of the PLA. Currently there is PLA45 (PLA which melts at ~195°C) and there will be PLA90 (High temperature PLA which melts at ~210°C). See the [Orbi-Tech Webshop](http://www.orbi-tech.de/shop/Plastic-Welding-Rod/PLA:::30_46.html "Orbi-Tech Webshop") for specific characteristics.
* ZX.XX -- Height of the layers in mm
* nr -- creates no raft
* r -- creates raft
* x -- Times speed (16mm/s is 1.0)
* fine -- Indicates thin walls

## Installation

Put both the *alterations* folder and the *profiles* folder into your *.skeinforge* folder. On Mac and Linux this is in your Home directory (`~/.skeinforge`), on Windows it is in `C:\Users\<Your Username>\.skeinforge`.

## Raft

You can enable the raft for any profile. Select the *raft* tab and set both *Base Layer* and *Interface Layers* to *1*. A raft is especially useful when the model won't stick to the build platform properly.

## Support

To print models with overhangs greater than 45°, it is recommended to use support material. To enable support material, select the *raft* tab and set *Support Material Choice* to *Everywhere*. 