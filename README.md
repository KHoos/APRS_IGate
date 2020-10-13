# APRS_IGate
APRS IGate

Source code for the PI4RAZ Igate

# How to build

Add ESP32 support to an Arduino IDE environment

Instructions for this step at https://github.com/espressif/arduino-esp32/blob/master/docs/arduino-ide/boards_manager.md

The code for the ESP32 module in this project is in [APRS_IGate.ino](APRS_IGate.ino). Load this code into the Arduino IDE,
select 'Board: FireBeetle-ESP32' or 'Board: ESP32 DEV module', 'Flash Frequency: 80 MHz', 'Upload Speed: 921600'.

Now it is possible to upload the code to the ESP32. If the ESP32 will not accept programming, restart it with the BOOT button
and press EN short to get it into programming mode.
