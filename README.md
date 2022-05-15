# STM32CubeMX Board Definitions
A collection of STM32CubeMX Hardware profiles for development boards e.g. WeAct Mini Black Pill

Contributions most welcome. This is repository is in phase Alpha 0.0.1 :)

# Board Definitions
* STM32VLDiscovery STM32F100RBT (STM32F1xx)
* STM32F411CEU6 (STM32F4xx)

## STM32VLDiscovery STM32F100RBT (STM32F1xx)
I bought this board when it first came out (was that over 10-15 years ago for AU $12 ?),but never did much with it due to time. Whilst the WeAct32F411 was with the courier I did an initial prototype for a client with this board. Quite simple, just a couple of PWM used to glow the LEDs and control a vacuum controlled solenoid connected to a 2" butterfly valve. Worked a treat.
The board definition includes all pins associated with an LCD board expansion kit: EB-STM32DISCOVERY-LCD
The expansion board has build in LED backlight driver circuit and 60pin FPC connector for the Kentec LCDs
(3.5 inch: K350QVG-V2-F; 4.3 inch: K430WQC-V3-FF; 5.0 inch: K50DWN2-V1-FF; 7.0 inch: K70DWN2-V1-FF;
9.0 inch: K90DWN2-V1-FF).

## STM32F411CEU6 (STM32F4xx)
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

## STM32F411VETx
This is an LQFP100 package for the STM32F4. I picked this as it was an available stock item from https://jlcpcb.com/ a site I randomly came across that provided what appears to be a good PCB manufacture and component assembly service. The STM32F411CEU6 was not available. The advantage of the VE series and LQFP100 is the expanded pin count. I find the Black Pill suffers on physical IO availability. The VLDiscovery was a much better IO combination. As is the STM32H750VBT6 below.

## STM32H750VBT6 WeAct Mini
Work in progress. Assistance probably needed to nut out the external memory interfaces
