# Temperature, Pressure, Humidity and Battery

Parts:
======
Rev 1:
- 1 Arduino MKR 1010 WIFI
- 1 Adafruit BMP 280 sensor
- 1 Bread Board
- 1 battery LI-ON 3.7V / 2000 mAH
- Some wires

Rev 2:
- 1 Arduino MKR 1010 WIFI
- 1 Adafruit BMP 280 sensor
- 1 Bread Board
- 1 battery LI-ON 3.7V / 2000 mAH
- Some wires
- 0.96 Inch OLED Display SSD1306 I2C 128*64

Rev 3:
- 1 Arduino MKR 1010 WIFI
- 1 BME 280 sensor
- 1 Bread Board
- Some wires

Board Rev 1:
============
![board](https://github.com/destouma/envsensing/blob/master/Board/EnvSensingRev1.jpg)


BLE Software (Rev 1):
=====================
Folder: EnvSensingBle

Temperature / Pressure / Battery Level

Environmental Sensing Service:
https://www.bluetooth.com/xml-viewer/?src=https://www.bluetooth.com/wp-content/uploads/Sitecore-Media-Library/Gatt/Xml/Services/org.bluetooth.service.environmental_sensing.xml

Battery Service:
https://www.bluetooth.com/xml-viewer/?src=https://www.bluetooth.com/wp-content/uploads/Sitecore-Media-Library/Gatt/Xml/Services/org.bluetooth.service.battery_service.xml

BLE Software (Rev2):
====================
Folder: EnvSensingBleRev2

Temperature / Pressure / Battery Level

Environmental Sensing Service:
https://www.bluetooth.com/xml-viewer/?src=https://www.bluetooth.com/wp-content/uploads/Sitecore-Media-Library/Gatt/Xml/Services/org.bluetooth.service.environmental_sensing.xml

Battery Service:
https://www.bluetooth.com/xml-viewer/?src=https://www.bluetooth.com/wp-content/uploads/Sitecore-Media-Library/Gatt/Xml/Services/org.bluetooth.service.battery_service.xml


WiFi Software (http) (Rev 1):
=============================
Folder: EnvSensingWifi

Temperature / Pressure / Battery Level

Http Client is posting to the rest api env-sensing-api


WiFi Software (mqtt) (Rev 1):
=============================
Folder EnvSensingMQTT

Temperature / Pressure / Battery Level

change you wifi settings in arduino_secret.h

change you broker ip


WiFi Software (http) (Rev 3):
=============================
Folder: EnvSensingWifiRev3

Temperature / Humidity / Pressure

Http Client is posting to the rest api env-sensing-api 


Not connected Software (Rev 2):
===============================
Folder: EnvSensingRev2

Temperature / Pressure / Battery Level

