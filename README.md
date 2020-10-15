# Weather boat sensors

External Signal K sensors configured for a ESP8266 (Adafruit Feather HUZZAH with ESP8266) with a BME280 sensor.

## Requirements

* Signal K running
* PlatformIO installed 

## Diagram

```shell
Huzzah --- BME280
GND    --- GND
3V     --- VIN
SCL    --- SCL
SDA    --- SDA
```

## Usage

Open project in PlatformIO, build and push binary to device. Once runnning, find the new WiFi network and set this to your Wifi network OR your boat controller.

Next open `security` settings in Signal K (`http://<ip-address>:3000`), find the new device and allow for `read/write`. Set expiry to `NEVER`.



