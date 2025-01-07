# Picotracker Alt-PCB

**Do not fabricate! There could be a major mistake around MIDI!!**

This project is about [democloid picoTracker's](https://github.com/democloid/picoTracker/) alternative PCB.
Inexpensive handheld devices can be built to run LittleGPTracker(a.k.a piggytracker).
It basically follows the original DIY version, with a few modifications of my own. They are described below.

[You can see it in motion here.](https://www.instagram.com/p/C2BvngaruZN/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==)

<img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/picotracker-front.jpg" width="400"><img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/picotracker-back.jpg" width="400">

## Feature

- The two PCBs act as an enclosure by sandwiching the components together.
- I wanted a module for the charging function and plenty of memory, so I went with the [Pimoroni Pico LiPo](https://shop.pimoroni.com/products/pimoroni-pico-lipo).
- I wanted a micro-speaker like the DirtywaveM8, so I added one... and a Class D amplifier module.
- A speaker kill switch has been added.
- This also uses Kailh Choc V1 for the keycaps because of my personal taste.
- You can change any specification by yourself if you have access to Kicad.
- [See image for values of components around MIDI.](https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/MIDI_resistor_value.jpg)
- I designed a back panel that could be output with a 3D printer because I felt the microspeaker needed box resonance. Also, if you would like to try it, please see the STL data. Feedback is welcome.
- <img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/3d_BP.png" width="400">

## BOM
| Value | Quantity | info |
| ---- | ---- | ---- |
| Pimoroni Pico LiPo 16MB | 1 | [URL](https://shop.pimoroni.com/products/pimoroni-pico-lipo)　 [URL(Japan only)](https://akizukidenshi.com/catalog/g/g116997/)  |
| ILI9341 3.2" display | 1 | [URL](https://www.aliexpress.us/item/3256802819098352.html) |
| GY-PCM5102 DAC module | 1 | [URL](https://www.aliexpress.us/item/3256802711963831.html) | 
| Adafruit Micro SD SPI or SDIO Card Breakout Board | 1 | [URL](https://www.adafruit.com/product/4682) | 
| Kailh Choc V1 key switch | 9 |  | 
| keycaps | 9 |  |   
| max98306 class D amp | 1 | [URL](https://ja.aliexpress.com/item/1005004990814956.html)  |
| Micro speaker | 2 | [URL](https://akizukidenshi.com/catalog/g/gP-12494/)  |
| SMD Slide Switch | 1 | on-on [The footprint uses a 6-pin one.](https://akizukidenshi.com/download/ds/switronic/IS-2245S-G.PDF) |
| PJ-311 3.5mm Stereo Jack | 2 |  |
| 1n4148| 1 | SOD-323 |
| 47R | 2 | 1608 |
| 220R | 1 | 1608 |
| 470R| 1 | 1608 |
| 6N138 | 1 | DIP-8 SMD(Just cut off the normal DIP8 leg.) |
| lipo battery | 1 | I use 1200mAh and need less recharging. |
| other | * | Other pin headers and sockets. We need standoff bolts, nuts, screws, and lots of them. |

It is recommended to use short pin headers and to solder directly without using sockets. At the very least, the effective depth of the 3D printer back panel is only 11 mm, which would interfere with the use of pin sockets. (but i wanted to go thin)



The images below are prototype versions and differ from the actual data.

<img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/1.jpg" width="400"><img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/2.jpg" width="400">



