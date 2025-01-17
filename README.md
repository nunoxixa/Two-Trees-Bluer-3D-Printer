# Two Trees BlueR - 3D Printer

Documentation, firmware and set of utilities for my own use and personal needs.

<p align="left"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/Printer%20Preview.jpg" width="50%" height="50%"></p>

## Hardwarede Specs
| Parameter | Value |
|--|--|
Number of nozzles|1|
Construction volume|235mm * 235mm * 280mm|
Printing method|SD-Card / online printing (by Serial UART communication through printer USB connector and some internet interface)|
IHM|3.5 inch color touch screen|
Machine speed|10~300mm/s|
Print speed|20~200mm/s|
Extrusion head temperature (highest)|260 °C|
Maximum hot bed temperature (highest)|100 °C|
Printing platform|Warm bed|
XY axis positioning accuracy|0.01mm|
Z axis positioning accuracy|0.004mm|
Recommended printed material|PLA, ABS and PETG|
Consumable filament diameter|1.75mm|
Print file format|G-Code|
Machine size|L=410mm * W=400mm * H=520mm|
Machine weight|7.5kg|
Power supply|127V~220V/240W|
Microcontroller|[STM32F103VET6 datasheet](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Motherboard/2.%20Datasheets/MCU/STM32F103VET6.pdf)|
Motor Driver|[TMC2209 datasheet](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Motherboard/2.%20Datasheets/Stepper%20Motor%20Driver/TMC2209.pdf)|
Stepper Motor|[US-17HS4401S datasheet](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Stepper%20Motors/US-17HS4401S.pdf)|
Motherboard|[MKS Robin Nano v1.2 schematic](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Hardware/Motherboard/1.%20Schematic/MKS%20Robin%20Nano%20v1.2.pdf) ([source HW + FW](https://github.com/makerbase-mks/MKS-Robin-Nano-V1.X))|
Display|MKS Robin TFT35(FSMC) (schematic not available)|

More information on the manufacturer's website: https://www.twotrees3dprinter.com

## Firmware
Versions|[Marlin 3D Printer Firmware](https://github.com/MarlinFirmware/Marlin/releases/tag/2.0.8) (from release-2.0.8 in 4/30/2021) + [BlueR v3 Marlin Configurations](https://github.com/MarlinFirmware/Configurations/tree/release-2.0.8/config/examples/Two%20Trees/BlueR/BlueR%20V3) (from release-2.0.8 in 4/30/2021) + Personal Customization|
--- | ---


## Print Samples

### Decoration Models
#### Among Us ([STL](https://www.thingiverse.com/thing:4626168))


![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/Among%20Us%200.png) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/Among%20Us%201.png)
--- | ---

#### Bulbasaur Planter ([STL](https://www.thingiverse.com/thing:633081))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201103_212945.jpg" width="80%" height="80%"></p>


### Tools & Utensils
#### SD & Micro SD Card Box ([STL](https://www.thingiverse.com/thing:3611322))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201107_093354.jpg" width="80%" height="80%"></p>

#### 18650 Battery Box (x8) ([STL](https://www.thingiverse.com/thing:3191180))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201108_102735.jpg" width="80%" height="80%"></p>

#### Dust Filament Filter ([STL](https://www.thingiverse.com/thing:1692395))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103905.jpg" width="80%" height="80%"></p>

#### Universal Filament Clip ([STL](https://www.thingiverse.com/thing:3757356))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103758.jpg" width="80%" height="80%"></p>


### Calibration & Tests
#### XYZ Cube ([STL](https://www.thingiverse.com/thing:1278865))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_103646.jpg" width="80%" height="80%"></p>


### BlueR Self-Upgrades Parts
#### BLTtouch Support (front mounting) ([STL](https://moltech3d.com/blog/2020/10/05/suporte-para-fixacao-do-bltouch-na-impressora-twotrees-bluer/))
<p align="center"><img src="https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/IMG_20201114_123223.jpg" width="80%" height="80%"></p>

## Improved Components and Updates
- [x] Stepper Motor Driver - [TMC2209](https://br.banggood.com/5pcs-TMC2209-Stepper-Motor-Driver-Super-Silent-Stepsticks-Mute-Driver-Board-256-Microsteps-For-Sidewinder-3D-Printer-p-1585178.html?rmmds=myorder&cur_warehouse=CN) at X, Y, Z and E - **ultra-silent controllers**
- [x] Auto Leveling Sensor - [3D Touch](https://br.banggood.com/TWO-TREES-Touch-Auto-Leveling-Sensor-Auto-Bed-Leveling-Sensor-BLTouch-For-3D-Printers-p-1625266.html?rmmds=myorder&cur_warehouse=CN) - **Automatic and improved bed leveling**
- [x] Glass on the heated bed plate [235mm x 235mm x 4mm](https://pt.aliexpress.com/item/32919815984.html?spm=a2g0o.productlist.0.0.2c6f467ef8q7mg&algo_pvid=a9dc1c8f-cf32-4685-b677-53a1c3206704&algo_expid=a9dc1c8f-cf32-4685-b677-53a1c3206704-0&btsid=212bd07d16173281806017826e8910&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_) - **better adhesion and flatness surface**
- [x] Anti-backlash Spring Loaded Nut - [T8](https://pt.aliexpress.com/item/32820989850.html?spm=a2g0o.cart.0.0.4d623c00aKJcGs&mp=1) - **Smooths lines on the z axis**
- [ ] Wireless Printer Monitor and Controller - [Raspberry](https://www.raspberrypi.org/) + [OctoPi](https://github.com/guysoft/OctoPi) + [OctoPrint](https://octoprint.org/) + [Sonoff](https://sonoff.tech/)
- [ ] Premium Ultra-Quiet Fan Cooler - [Noctua NF-A4x10 FLX](https://noctua.at/en/nf-a4x10-flx) + [DC-DC Buck Converter with LM2596](https://br.banggood.com/LM2596-DC-DC-Verstellbar-Step-Down-Schaltregler-Power-Supply-Module-p-88252.html?rmmds=search&cur_warehouse=CN)
- [ ] Silicone cover for heated block - [MK8 Cover](https://www.aliexpress.com/item/33050074990.html?spm=a2g0o.detail.0.0.4574ac8c3xkbkY&gps-id=pcDetailBottomMoreThisSeller&scm=1007.13339.169870.0&scm_id=1007.13339.169870.0&scm-url=1007.13339.169870.0&pvid=c34b10de-e1c6-47de-9053-f818f89dd91a&_t=gps-id:pcDetailBottomMoreThisSeller,scm-url:1007.13339.169870.0,pvid:c34b10de-e1c6-47de-9053-f818f89dd91a,tpp_buckets:668%230%23131923%2330_668%23808%234094%23253_668%23888%233325%2312_668%234328%2319926%23211_668%232846%238116%23942_668%232717%237558%23186_668%231000022185%231000066058%230_668%233468%2315616%23763)


## Printer Details
| ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/1.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/2.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/3.jpg) |
|--|--|--|
| ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/4.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/5.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/6.jpg) |
| ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/7.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/8.jpg) | ![](https://github.com/TiagoPaulaSilva/Two-Trees-Bluer-3D-Printer/blob/master/Assets/10.jpg) |
