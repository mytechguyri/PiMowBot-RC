# PiMowBot-RC
![picoRC 4 PiMowBot!](/Logo.jpg "picoRC 4 PiMowBot") 
This is the code of **RControl 4 PiMowBot** ( http://pimowbot.tgd-consulting.de ).
___
Here you can find the source code of the pico RC remote control for the PiMowBot ( http://pimowbot.tgd-consulting.de ).

The RC (Remote Control) requires at least these components:
Raspberry Pi Pico W
Pico LCD 1.14inch display module from Waveshare
Custom MicroPython uf2 firmware by Pimroni ( https://github.com/pimoroni/pimoroni-pico/releases/download/v1.19.9/pimoroni-picow-v1.19.9-micropython.uf2 )
The RCjoy requires at least these components:
Raspberry Pi Pico W
round SPI LCD 1.28" display module 240x240 with GC9A01 driver
analog joystick
Custom MicroPython uf2 firmware by Russ Hughes ( https://github.com/russhughes/gc9a01_mpy/blob/main/firmware/RP2W/firmware.uf2 )
Commissioning the RC in three steps:
Flash the Pico W with the appropriate Custom MicroPython uf2 firmware.
With the help of the Thonny IDE ( https://thonny.org/ ), these files ( Logo.jpg and RControl.py or Logo240.jpg and RCjoy.py ) of the repository are transferred to the flash memory of the Pico W.
Before executing the RControl.py / RCjoy.py script, the values ​​for _SSID , _PASSWORD , _HOST and _TOKEN should be adjusted accordingly at the beginning of the respective MicroPython script.
!Important!
Your PiMowBot needs a current release (status: November 24, 2022 ) so that the image transfer to the RC works.
