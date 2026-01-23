# LedClock-AIO

 All In One (PCB) version of the **[ledclock](https://github.com/imeszaros/ledclock)** project by [imeszaros](https://github.com/imeszaros) and powered by [WLED](https://github.com/wled/WLED).

 ![IMG_0344s](https://github.com/user-attachments/assets/64c292a2-6a36-4587-9deb-21198bab14c3)

## Description and features

This version features an **ALL IN ONE** (AIO) approach for the **[ledclock](https://github.com/imeszaros/ledclock)** project by [imeszaros](https://github.com/imeszaros). 

The PCB was specifically designed to be under 100mm so it will cost less to produce it. 

The board can be powered with a USB-C cable.

All the components can be soldered by hand, some of the footprints are modified to allow this, but I still recommend you to **order a stencil** as well, at least for the FRONT of the PCB (where the LEDs are), because otherwise is gonna be quite hard (and time consuming) to hand solder all those LEDs.

![leds](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_9199.JPEG)

Schematic file also include some cheaper alternatives, for photosensitive sensor and potentiometer that you can find them on [lcsc.com](https://www.lcsc.com/) by searching the part no. listed below them (example: C242253 - for the photosensitive sensor alternative). **I did not include the alternative parts in the BOM to avoid confusion.** 

## LEDs alternatives
 You can also use [WS2812B-2020](https://www.lcsc.com/product-detail/C965555.html) LEDs which are a bit more expensive, as well as [TCWIN TX1812ZN](https://www.lcsc.com/product-detail/C784563.html) (which are a little bit bigger), but keep in mind that you have to **double/triple check the pin orientation** since the silkscreen marks doesn't match.

 ## Assembly instruction and tips

 Print the case files from the CaseModel folder of this repository in the colours that you like.  You can also find the files here : https://www.printables.com/model/1087560-led-clock-all-in-one-pcb-powered-by-wled
 
![case1](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_1790.JPEG)
 
 You will also need two M3 heat inserts and two M3x8mm CSK screws. 
 
 ![heatinsert](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/img-20241127.jpg)
 
 Segment covers need to be printed with a transparent filament, 20-30% infill, and 2-3 top/bottom layers. Depending on your printer accuracy you might want to print the offset segments file (which are 0.1mm smaller) . 
 
 **In order to keep track of them I place a masking tape over them before removing them from the plate and then place piece of kitchen  stretch film over the tape.**
 
![segments cover](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_1773.JPEG)
 
If the tolerances are too tight and you have problems inserting those segments cover, you can use a small hammer to "tap" the segments a little bit :)).

![hammer](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_9272.JPEG)
![segments in place](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_1794.JPEG)

## Firmware
Firmware is provided by the awesome work of [imeszaros](https://github.com/imeszaros). 

Just connect the Led Clock onto the computer (be sure you have CH340 drivers installed) and use [this tool](https://imeszaros.github.io/ledclock/) to flash the board (be sure to select de proper COM port). 

Download the WLED app from your phone's store and connect the clock in order to change the colors. 
- Google Play:  https://play.google.com/store/apps/details?id=ca.cgagnier.wlednativeandroid
- Apple App Store: https://apps.apple.com/us/app/wled-native/id6446207239

A detailed guide can be found here https://github.com/imeszaros/ledclock/blob/main/ledclock/users-guide.md

**ENJOY !**

![final picture1](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_0344.JPEG)
![final picture1](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/img-20241126.jpg)
![final picture1](https://github.com/mariusmym/LedClock-AIO/blob/main/Images/IMG_1823.JPEG)


