# STM32CubeMX - STM32F4

Contributions most welcome.

[Back to Main README](../../README.md)

[Back one level](../README.md)

# Board Definitions
* STM32F411CEU6 (STM32F4xx) WeAct Black Pill V3.1
* STM32F411VETx

## STM32F411CEU6 (STM32F4xx) MiniSTM32F4x1
### Overview
This board setup is modelled on the awesome WeAct STM32F411CEU6 Black Pill or MiniF4. You can find it here: https://github.com/WeActTC/MiniSTM32F4x1
The official store for purchases is https://weactstudio.aliexpress.com/store/910567080?spm=a2g0o.store_pc_home.pcShopHead_6000122603279.0
I bought a board unknowingly through eBay that looked exactly like a WeAct V3.0 board. One board was DOA as soon as I plugged the USB cable in it. The other worked for 3 days via an ST Link V2. But died after 10 minutes on USB-C. They were returned for a full refund.

For the board definition I have incorporated pins used in some of the examples, primarily the board caters for:
* STM32F411CEU6 Operating at 96MHz from 25MHz Crystal
* Button KEY
* BLUE LED
* ST Link V2
* USB C
* 8MB SPI Flash
* ST7735 128 x 160 LCD Display

The STM32F4 Black Pill Board Pinout is shown below (Compliments from [WeActTC MiniSTM32Fx1 project](https://github.com/WeActTC/MiniSTM32F4x1))
![STM32F4 Black Pill Board Pinout](STM32F4x1_PinoutDiagram_RichardBalint.png)

The Black Pill pin assignments for the STM32CubeMX file is shown below. It should suport the various test projects within minimal if any modification.
![Black Pil MCU Pinout](./STM32F111CEU6%20WeAct%20Mini%20V31%20MCU%20Pinout.png)

Black Pill Sample Clock configuration found in the IOC file.
![Black Pill Sample Clock Configuration](./STM32F411%2096MHz%20config%20from%2025MHz%20Crystal.png)

### Hardware Reference and Documents

* [Black Pill Schematic V3.1](./Hardware/MiniF4x1Cx_V31.pdf)
* [Black Pill Board Shape](././Hardware/MiniF4x1Cx_V31%20Board%20Shape.pdf)

### Useful Links
* [WeActTC GitHub](https://github.com/WeActTC)
* [Roger Clark Melbourn Arduino STM32 Blue Pill Black Pill](https://github.com/rogerclarkmelbourne/Arduino_STM32)
* [Roger Clark Melbourn Flashing Bootloader for BluePill Boards](https://github.com/rogerclarkmelbourne/Arduino_STM32/wiki/Flashing-Bootloader-for-BluePill-Boards)
* [STM32Duino Libraries](https://github.com/stm32duino/wiki/wiki/Libraries)