# Open Smartwatch

<img src="assets/renders/logo.png" width="384px"/>

## Current Status

* GPS Edition
    - PCB: still under development
    - 3D printable case: TODO

* Light Edition
    - PCB: [Released v3.2](https://github.com/Open-Smartwatch/open-smartwatch-light/releases/tag/v3.2)
    - 3D printable case: ready

Click on an image below to see some demos:

<a href="https://www.instagram.com/p/CJ0kNxRrvyN/" target="_blank"><img src="assets/media-links/update-10.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CJpAeQTLxKy/" target="_blank"><img src="assets/media-links/update-9.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CJblPtjLbKY/" target="_blank"><img src="assets/media-links/update-8.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CHYqOoEqUUx/" target="_blank"><img src="assets/media-links/update-7.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CHWNOh-KswS/" target="_blank"><img src="assets/media-links/update-6.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CG4RQgAL288/" target="_blank"><img src="assets/media-links/update-5.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CG7JhVLKmCw/" target="_blank"><img src="assets/media-links/update-4.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CFM6PhgKQAZ/" target="_blank"><img src="assets/media-links/update-3.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CEaALDAKkrY/" target="_blank"><img src="assets/media-links/update-2.png" width="192px"/></a>
<a href="https://www.instagram.com/p/CEXmMHgqWuu/" target="_blank"><img src="assets/media-links/update-1.png" width="192px"/></a>

## Goals

The goal is to build an open source smartwatch, with step counting, GPS tracking and maps.

- ESP32 (Arduino programmable)
- GPS
- Time
- Sensors (Acceleromter, Step Counting)
- Li-Ion Battery
- USB Serial
- uSD Card (to provide open streetmap tiles)

## Media Coverage

- hackster.io: [Something ESPecially Impressive about the Open-Smartwatch Project](https://www.hackster.io/news/there-s-something-especially-impressive-about-the-opensmartwatch-project-c2c878b983cf)

## Join the Discussion

* Discussions happen on Discord: [Pauls 3D Things](https://discord.gg/9DK5JY6) 
* Github organization: [https://github.com/Open-Smartwatch](https://github.com/Open-Smartwatch)

## Hardware

### GPS Edition

* PCB Source Files (KiCAD): [https://github.com/Open-Smartwatch/open-smartwatch-gps](https://github.com/Open-Smartwatch/open-smartwatch-gps)
* BOM: [https://htmlpreview.github.io/?https://github.com/Open-Smartwatch/open-smartwatch-light/blob/master/docs/bom/osw-light-ibom_v.html](https://htmlpreview.github.io/?https://github.com/Open-Smartwatch/open-smartwatch-light/blob/master/docs/bom/osw-light-ibom_v.html)
* 3D Files: [https://github.com/Open-Smartwatch/3d-files/tree/master/case](https://github.com/Open-Smartwatch/3d-files/tree/master/case)

[![front](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-gps/master/docs/img/osw-top.svg)](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-gps/master/docs/img/osw-top.svg)
[![bottom](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-gps/master/docs/img/osw-bottom.svg)](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-gps/master/docs/img/osw-bottom.svg)

[![Schematic](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-gps/master/docs/img/osw-schematic.svg)](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-gps/master/docs/osw-schematic.pdf)


### Light Edition

* PCB Source File (KiCAD): [https://github.com/Open-Smartwatch/open-smartwatch-light](https://github.com/Open-Smartwatch/open-smartwatch-light)
* Order PCB here: [https://aisler.net/p/EBEIQYQD](https://aisler.net/p/EBEIQYQD) (Hint: AISLER sponsored the PCBs for protoyping this project, hence the logo on the PCB ;) )
* BOM: [https://htmlpreview.github.io/?https://github.com/Open-Smartwatch/open-smartwatch-light/blob/master/docs/bom/osw-light-ibom.html](https://htmlpreview.github.io/?https://github.com/Open-Smartwatch/open-smartwatch-light/blob/master/docs/bom/osw-light-ibom.html)
* 3D Files: [https://github.com/Open-Smartwatch/3d-files/tree/master/case-light](https://github.com/Open-Smartwatch/3d-files/tree/master/case-light)


[![front](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-light/master/docs/img/osw-light-top.svg)](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-light/master/docs/img/osw-light-top.svg)
[![bottom](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-light/master/docs/img/osw-light-bottom.svg)](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-light/master/docs/img/osw-light-bottom.svg)

[![Schematic](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-light/master/docs/img/osw-light-schematic.svg)](https://raw.githubusercontent.com/Open-Smartwatch/open-smartwatch-light/master/docs/img/osw-light-schematic.svg)

## Software 

Repositories:

* Open-Smartwatch OS: [https://github.com/Open-Smartwatch/open-smartwatch-os](https://github.com/Open-Smartwatch/open-smartwatch-os), see Readme.md
* Open-Smartwatch Libraries: [https://github.com/Open-Smartwatch/lib-open-smartwatch](https://github.com/Open-Smartwatch/lib-open-smartwatch), see Readme.md



## Super-Quick-Start Guide 

After adding the OS to VScode with PlatformIO (recommended tutorial: https://youtu.be/JmvMvIphMnY (external link to YouTube)) you can change the config.h.example file in ./include to suit your data, and change it to a header file (remove .example). 
For uploading, you need to hold the lower left button and then click the reset button (top left). It enables flash mode, the display should get dark. Orientation for the display: USB insert at the left side. 
App changer works by holding the lower left button to switch to your desired app. 
