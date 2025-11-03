# OnStep Smart Web Server
This is the WiFi and Ethernet web server for OnStep, it is also sometimes referred to as the "SWS".
The SWS enables OnStep to be controlled from a website and/or by passing commands over IP.
The SWS is known to work from personal computers (using a web browser, ASCOM, or INDI), phones (Android and iOS), tablets, and the wireless Smart Hand Controller.

This is the WiFi and Ethernet webserver for OnStep.
It also enables OnStep to be controlled over IP. This access can be over command channel(s) and/or website.
This server is known to work from personal computers (using a browser), phones and tablets,
(using the Android OnStep App), Sky Safari, and my ASCOM driver (PC.)

# Installing the board Platform for your hardware
Before you can flash the firmware on your ESP8266 or ESP32 device, you need to install the ESP8266 OR ESP32
platform for the Arduino IDE.  If using an Arduino M0 or Teensy you don't need to perform this step.  For the
Teensy's you instead need to install the Teensyduino.exe package to add support to the Arduino IDE.

Under the menu File->Preferences open the dialog and add this line in the additional "Boards Manager" area:
  http://arduino.esp8266.com/stable/package_esp8266com_index.json,https://dl.espressif.com/dl/package_esp32_index.json


Then, from the "Tools, Boards, Boards Manager" menu select and install the ESP8266, ESP32, etc. as required.  

# Flashing The Smart Web Server
The exact flashing procedure depends on which device you will be using.  You can find instructions for setting up the SWS in its Wiki here:
https://onstep.groups.io/g/main/wiki/26881

# License
The Smart Web Server is open source free software, licensed under the GPL.

See [LICENSE.txt](./LICENSE.txt) file.

# Primary Author
[Howard Dutton](http://www.stellarjourney.com)
