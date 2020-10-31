# NodeMCU-DHT-Temperature-and-Humidty-Server
A server that displays temperature and humidity from a DHT sensor used on a NodeMCU

# Purpose
This projects allows you to attach a DHT sensor to a NodeMCU module. You can then use the `json` path to retrieve temperature and humidity readings compatabile with the [homebridge](https://github.com/homebridge/homebridge) plugin
[vknabel/homebridge-http-temperature-humidity](https://github.com/vknabel/homebridge-http-temperature-humidity) to attach to Apple's HomeKit.

# Dependencies
- [adafruit/Adafruit-Sensor](https://github.com/adafruit/Adafruit_Sensor)
- [adafruit/DHT-sensor-library](https://github.com/adafruit/DHT-sensor-library)
- [me-no-dev/ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer)
  - [me-no-dev/ESPAsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP)

# Credits / Tutorial
Almost all the code comes from [a blog post by Rui Santos at Random Nerds Tutorial](https://randomnerdtutorials.com/esp8266-dht11dht22-temperature-and-humidity-web-server-with-arduino-ide/).
The modified code exposes the `json` path and includes minor updates.
