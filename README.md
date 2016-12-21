# esp8266deepsleep - Testing Deep Sleep Mode of ESP8266-12E

This little code snippets are used to test the deep sleep function of ESP8266-12E devices flashed with the nodemcu firmware.
The method node.dsleep(int microseconds) accepts microseconds as its parameter. 1000000 ms = 1 s

Deep sleep consumes about 2µA, compared to 80 - 120 mA when the device is active.
