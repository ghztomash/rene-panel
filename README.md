[![Discord](https://img.shields.io/discord/690660866475032596)](https://discord.gg/vHcUuzN)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

# Make Noise René Panel

![Rene Panel](rene.jpg)

Alternative panel for [Make Noise René v1](https://www.makenoisemusic.com/modules/rene-classic-legacy). It solves the issue of conductive input not always working due to grounding issues and replaces them with mechanical switches for a more reliable function.

Designed by [Tomash GHz](https://tomashg.com/) in collaboration with El Campesino.

## Perview

[![Rene Panel Demo](https://img.youtube.com/vi/Lu6tKL7PgeA/hqdefault.jpg)](https://youtu.be/Lu6tKL7PgeA)

## Features
* Tactile mechanical switches.
* Solves grounding issues.
* Improves panel font readability.

## Bill of Materials

| Part Number | Manufacturer | Count | Description |
| --- | --- | --- | --- |
| PTS125SM43LFS | C&K | 16 | 12x12x4.3 mm Through Hole Switch |
| PTS645SM432LFS | C&K | 2 | 6x6x4.3 mm Through Hole Switch |
| 963105-2000-AR-PR | 3M | 4 | 5 pin SMD Female Headers* |

* Alternatively you can use 4 x 6 pin headers, 2 x 10 pin headers, 2 x 12 pin headers. Whatever is easier to get.

Note: On the back there are optional footprints for resistors and capacitors to debounce the switches. Those are really not necessary to populate. 
But if you do decide to populate them, you can use some values like 120R and 100nF and break the corresponding SB briges.

## Instructions

To assemble the panel:
* Solder the through hole 6mm and 12mm switches to the new panel. (if you are using Omron 12mm switches you need to cut the positioning pegs).
* Remove the jack nuts from Rene and carefully lift the old panel.
* Take the SMD headers and carefully fit them on the male pins of the main board.
* Place the new panel onto the main board, carefully aligning all the LEDs and Jacks into their coresponding holes.
* Screw back 2 x jack nuts.
* Allign the Female SMD headers so that they touch their corresponding pads on the panel.
* Carefully solder from the side a pair of pads for each SMD header. (try to do at least two pads on oposite side of each the header).
* Remove the panel again, and solder the rest the Header pads from the other side.
* Place everything back and screw the jack nuts.
* Have fun!

Note: If you have a problem with qCV, make sure the C button don't touch the trimmer that is right underneath it. Either use a soldering iron to make the joint shorter, or put a tiny piece of duct tape on top of the trimmer.
