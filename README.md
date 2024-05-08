# OSD Control Board
This OSD board is a simple set of logic gates that allow the screen driver boards used in portables to be controlled with button combinations from the built-in controller. This was a first-rev board *very* early venture into PCB design, so it could definitely use some tweaks like decoupling caps for the logic gates, and the use of a proper ground plane. The board works fine as-is, or you could integrate it into your own design!

## Using the Board
LT, RT, Z and S held together trigger the master key which, in combination with the following buttons will trigger the outputs wired to the screen driver board:
- DU: +
- DD: -
- DL: Source
- DR: Menu

Keep in mind, you can change the master button combination (or any of the other buttons) to better fit to your portable. For example, I like to wire S on the OSD board to Z2 on my GC+ in all my Ashidas, as the original button combination was not ergonomic. Likewise, you can tie multiple inputs together if you want a master combo with less buttons.

<img src="https://github.com/CrazyGadgetMods/OSD-Control-Board/blob/main/images/assembled.jpg" height=300> <img src="https://github.com/CrazyGadgetMods/OSD-Control-Board/blob/main/images/g-boy install.jpg" height=300> <img src="https://github.com/CrazyGadgetMods/OSD-Control-Board/blob/main/images/ashida install.jpg" height=300>

## Credits
- [BitBuilt](https://bitbuilt.net/): Being the best modding community out there!
- [Gman](https://github.com/Gmanmodz): Sanity checking

## License
Solderpad Hardware License v2.1
