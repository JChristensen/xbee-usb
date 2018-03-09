# XBee USB Dongle
https://github.com/JChristensen/xbee-usb  
README file  
Jack Christensen Feb-2018

## Overview
This dongle was mainly intended to connect an XBee semi-permanently to a Raspberry Pi, neatly without cables, for communication with an application program. Of course it can be used with any other computer as well. It's also useful for programming an XBee with [Digi's XCTU utility](https://www.digi.com/products/xbee-rf-solutions/xctu-software/xctu), or as a range extender in the mesh network by just plugging it into a 5V wall wart, phone charger, etc.

Via a solder jumper on the back of the board, the XBee's reset pin can be connected either to a pushbutton switch or to the CBUS3 pin on the FTDI FT231X chip. To use CBUS3 as a reset line, configure it as a GPIO pin using [the FTDI FT_PROG utility](http://www.ftdichip.com/Support/Utilities.htm#FT_PROG).

PC boards can be ordered [from OSH Park](https://www.oshpark.com/shared_projects/egIOkt1Z).  
A bill of materials is available [at Mouser Electronics](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=f236469f0d) and also in this repo.

![](https://raw.githubusercontent.com/JChristensen/xbee-usb/master/boards-photo.jpg)

![](https://raw.githubusercontent.com/JChristensen/xbee-usb/master/rpi-with-xbee-dongle.jpg)

**Raspberry Pi Zero with [Zero4U USB hub](https://www.adafruit.com/product/3298) and XBee USB Dongle.**

## CC BY-SA
"XBee USB Dongle" by Jack Christensen is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).