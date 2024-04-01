# ESP32-TFT9431-Jpeg-Display
Display JPEG images on TFT 9341 display using ESP32 and SD card with images

Wiring setup between the ESP32 and TFT display:

In User_Setup.h
---------------
#define TFT_MOSI 23

#define TFT_SCLK 18  // Clock

#define TFT_CS   15  // Chip select control pin

#define TFT_DC    2  // Data Command control pin

#define TFT_RST   4  // Reset pin (could connect to RST pin)


Pin values not set in User_Setup.h
----------------------------------
SD_SCK      18

SD_MISO     19

SD_MOSI     23

SD_CS        5


