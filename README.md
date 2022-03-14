A small board designed to replace the proprietary Wii U dock charging port with a USB type C port.

Features:
* Includes pads for 5.1k&#937; resistors, to allow the use of 'smart' chargers.
* Pads on the + output allow the addition of a switch - bridge these pads with a 0&#937; resistor if you're not using one.
* Board is a near drop-in replacement for the original - only a small amount of sanding inside the dock is required.
* No alteration to the outside of the dock is necessary (unless you add a switch).

Included in this repository are the KiCAD files for this design. If you're only interested in having the board manufactured, gerbers are available under 'releases'.

Parts List:
* 1x 16 pin USB type C port
* 1x 0603 0&#937; resistor/1x 2 pin switch
* 2x 0603 5.1k&#937; resistors (optional)

A tri-wing screwdriver is required, to remove the dock base.

When having the board manufactured, ensure they offer a 0.8mm board thickness - I used OSH Park for mine.

For more information, take a look at [my blog post](https://qubitsandbytes.co.uk/post/convert-a-wii-u-dock-to-usb-c).

## Images
KiCAD render:

![KiCAD render](render.png?raw=true "KiCAD render of the board")

Dock with added switch:

![Dock with switch](dock-with-switch.png?raw=true "Dock with added switch")

## KiCAD
The files in this project were created using KiCAD 6, which introduced a new file format not compatible with older versions. Ensure you are using KiCAD 6 if you wish to open the files.

In addition, the USB Type C port pictured in the 3D render can be found [over here](https://github.com/ai03-2725/Type-C.pretty) - the file you're looking for is 'HRO TYPE-C-31-M-12.step'. It's not required, unless you want to see the part populated using the 3D viewer.
