NTP based clock for Wemos D1 mini and Wemos oled shield.
===

Personal fork of of G6EJD's fine: https://github.com/G6EJD/ESP8266-NTP-time-on-an-OLED-with-WiFi-Manager


Developed on Arduino 1.8.3

Changes:
* Set ntp check to every 15 minutes
* Change date display to US Default
* quoted "Adafruit_SSD1306.h" include to pull locally.


## Build instructions
Clone into your ~Ardunio directory, open in arduino IDE, compile, and install.
```
  cd ~/Arduino
    ~/Arduino $ git clone https://github.com/sboger/ESP8266-NTP-time-on-an-OLED-with-WiFi-Manager.git

Read about using WiFi Manager to setup.  AP mode, ip address, etc.
```
