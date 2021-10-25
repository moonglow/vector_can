# VN1610 firmware for STM32F4 based boards

#### Support me
Bitcoin:
<a href="https://www.buymeacoffee.com/moonglow" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" height="41" width="174"></a>

Target hardware:
* Any STM32F407/405 based boards with 8MHz oscillator

Pinout:
|PIN/PINS|DESCRIPTION|
| ------ | ------ |
|PC10|STATUS LED|
|PA2/PA3|TX/RX CAN1 LED|
|PC6/PC7|TX/RX CAN2 LED|
|PB8/PB9|CAN1 RX/TX|
|PB5/PB6|CAN2 RX/TX|
|PB14/PB15|USB DM/DP|

Features:
- Two channel USB<->CAN adapter
- Supports by XL-Driver-Library
- Supports by BusMaster

Limits:
- For education purpose only
- No license inside ( do not ask about it )
- Some protocol specific messages not implemented yet
- Be sure to use **PB14/PB15** pins for USB

License
----

WTFPL
