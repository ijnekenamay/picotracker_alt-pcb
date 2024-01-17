# Picotracker Alt-PCB

This project is about [democloid picoTracker's](https://github.com/democloid/picoTracker/) alternative PCB.
It basically follows the original DIY version, with a few modifications of my own. They are described below.

## Feature

- The two PCBs act as an enclosure by sandwiching the components together.
- I wanted a module for the charging function and plenty of memory, so I went with the [Pimoroni Pico LiPo](https://shop.pimoroni.com/products/pimoroni-pico-lipo).
- I wanted a micro-speaker like the DirtywaveM8, so I added one... and a Class D amplifier module.
- It has an in-line volume control. However, this should be handled by software, given the availability of components. (We will eventually remove it from the PCB.) Currently, to keep it DIY friendly, we are not specifying a specific footprint, but allowing the usual 2gang POTs to be installed by hand wiring.
- A speaker kill switch has been added.
- This also uses Kailh Choc V1 for the keycaps because of my personal taste.
- You can change any specification by yourself if you have access to Kicad.

The images below are prototype versions and differ from the actual data.
<img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/1.jpg" width="400"><img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/2.jpg" width="400">

<img src="https://raw.githubusercontent.com/ijnekenamay/picotracker_alt-pcb/main/images/3.png" width="400">
