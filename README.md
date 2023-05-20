# Modified for use on Raspberry Pi Pico

For display I used

`CS`  -> GP18
`RST` -> GP17
`DC`  -> GP16
`SDI` -> GP11 (SPI1 TX MOSI)
`SCK` -> GP10 (SPI1 SCK)

For touch I used

`T_CLK` -> GP2  (SPI0 SCK)
`T_DI`  -> GP3  (SPI0 TX)  (MOSI)
`T_DO`  -> GP4  (SPI0 RX)  (MISO)
`T_IRQ` -> GP5
`T_CS`  -> GP6

Notes: `demo_fonts.py` fails because of a Unicode decode error in `fonts/Neato5x7.c` (this file is not
valid UTF8.)

# micropython-ili9341
MicroPython ILI9341 Display and XPT2046 Touch Screen Drivers

Full write up on my website [Rototron](https://www.rototron.info/projects/esp32-pwned-password-checker/) or click picture below for a YouTube video:

[![ILI9341 Tutorial](https://img.youtube.com/vi/NJuOkSSfgUQ/sddefault.jpg)](https://youtu.be/NJuOkSSfgUQ )

_Tested on ESP32 (Wemos Lolin32 & Loline32 Pro)_

