# Instructions

## What to buy
- [ESP32 Microcontroller](https://a.aliexpress.com/_ExcwL9k)
- [GC9A01 TFT Display (240x240px)](https://a.aliexpress.com/_EuVPvME)

## Wiring
|GC9A01 Pin|ESP32 Pin|Description|
|------|------|------|
|VCC|3.3V|Power supply|
GND|GND|Ground|
|SCL/SCLK|GPIO 18|SPI Clock
|SDA/MOSI|GPIO 23|SPI Data|
|RES/RST|GPIO 4|Reset|
|DC|GPIO 2|Data/Command|
|CS|GPIO 5|Chip Select|
|BLK/BL|GPIO 22|Backlight (optional)|

Search for a pinout diagram of the board which shows the GPIO location

## PlatformIO Setup
1. Install PlatformIO Visual Studio Code Extension
2. Install "Adafruit GFX", "Adafruit GC9A01A" and AnimatedGIF library
3. Connect ESP32 Controller to PC
4. Click on Upload to compile and upload the main.cpp to the ESP32
5. Click on Alien in left VS Code toolbar then Miscellaneous > New Terminal
6. Run `pio run --target uploadfs`to upload the GIF located in the data folder (make sure no serial monitor is running)

## Print model parts

All parts can be found on Makerworld: https://makerworld.com/de/models/1859297-desk-hamster
Or use the stl files in the github repo

- Tray
- Cage
- Wheel
