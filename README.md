# wemos2018
Wemos d1 mini v2, May2018; Webtec 7.99; djmc485 6.80


Wemos D1 mini is similar to NodeMCU module, smaller, and have newer version of wifi module-12F. More stable and with a better range.  and can be program and powered directly from the usb port.

Wemos D1 module is populated with ESP8266-12F. On board there is also USB-UART converter (popular CH340). for usb programming.

Wemos D1 has 9 GPIO ports with PWM, I2C, SPI and 1-Wire support. The 3.3V LDO module can be powered directly from USB port.

They are 3 basic methods to use Wemos. AT commands, LUA programming language with NodeMCU firmware and simplest is with Arduino IDE.

Specification:

Embeded ESP8266-12F with PCB antena

Flash: 4MB

Wi-Fi in standard 802.11 b/g/n

WiFi modes: AP (Access Point), STA (Standalone), AP+STA

Supports TKIP, WEP, CRC, CCMP, WPA/WPA2, WPS

Supply voltage: 3.3V (or 5V via USB)

CPU: RISC 80MHz (supports up to 160MHz)

9 GPIO - PWM / I2C / SPI / 1-Wire

Max current on I/O pins: 12mA

Recommended current on I/O pins: 6mA

USB-UART converter - CH340

ADC - 10-bit

16 pins in 2,54mm raster - breadboard compatible

micro USB B

Size: 34 x 25mm

LED connected to GPIO2 (D4); 
note to activate onboard blue led:

 pinMode(2,OUTPUT); // gpio 2 or d4 wemos onboard blue light
 
 digitalWrite(2,HIGH); // HIGH is off
 
wemos  examples: https://github.com/wemos/D1_mini_Examples/tree/master/examples/01.Basics

-------

notes on wifi status:
WL_NO_SHIELD = 255,\
WL_IDLE_STATUS = 0,\
WL_NO_SSID_AVAIL = 1\
WL_SCAN_COMPLETED = 2\
WL_CONNECTED = 3\
WL_CONNECT_FAILED = 4\
WL_CONNECTION_LOST = 5\
WL_DISCONNECTED = 6\


builtin led: 
https://piandmore.wordpress.com/2016/10/10/esp-internal-led/


oled:\
https://automatedhome.party/2017/04/17/connect-an-inexpensive-oled-display-to-a-esp8266wemos-d1-mini/


