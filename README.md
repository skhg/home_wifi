# home_wifi
Common configuration library for personal Arduino WiFi projects

This library needs to be copied into the Arduino libraries folder in order to be available. On Mac this is `~/Documents/Arduino/libraries/`

Then it can be included in any other project using:

```cpp
#include<home_wifi.h>
```

And the configuration can be used, for example alongside `WiFiClient` from [ESP8266WiFi](https://github.com/esp8266/Arduino/tree/master/libraries/ESP8266WiFi), with:

```cpp
WiFi.begin(WIFI_SSID, WIFI_PASSWORD);
```
