# esp32-arduino-idf
ESP32-Arduino-idf
  using environment sensor make Air Quality sensor by ESP32 dev kit (dev kit c -v4) using Arduino-IDE
     sensor list 
       1. 18B20 (Temperature sensor - digital out / OneWire)
       2. SGP40 (VOC sensor - I2C)
       3. GP2Y1014 (Dust sensor - Analog out )
       
  
# Pin set. 
  1. 18B20 -> 3.3V / DQ/ GND
      - DQ = GPIO 15
  2. SGP40 -> 3.3V / GND / SCL / SDA
      - SCL = GPIO 22 / SDA = GPIO 21
  3. GP2Y1014 -> V-LED / GNd-LED / LED / GND / V out / Vcc
      - LED = GPIO 35   / V out (Analog out) = GPIO 34

# additional Library 
  1. 18B20 - OneWire (library requested)
  2. SGP40 - DFDFRobot_SGP40 (library requested)
  3. GP2Y1014 - Sharp GP2Y Dust Sensor (library requested)


# Reference
*youtube:
  for 18B20 Onewire
  - https://www.youtube.com/watch?v=P0aqbD9umDE
 *git hub
  for SGP40
   -https://github.com/sparkfun/SparkFun_SGP40_Arduino_Library
 *example used. 
    GP2Y1014  -> on the library has example source code.
