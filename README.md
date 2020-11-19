# MQ 135 Wifi Air quality sensor


This is a project involving the esp8266 and mq135 sensor to create a module which will be able to measure the air quality in a specific location and can be connected wirelessly to the internet.

Modules needed for this project and where they can be bought:

- [ESP8266 Microprocessor](https://amzn.to/2LbvQIa)
- [OLED Display](https://amzn.to/2L8X81F)
- [MQ135 on Amazon](https://amzn.to/39Ch4ny)
- [Breadboard](https://amzn.to/2YM6YyS)
- [Connecting wires](https://amzn.to/2L8Xc1p)


## Air Quality Index
The AQI is an index for reporting daily air quality. It tells you how clean or polluted your air is and how it may affect your health. The chart below mentions the levels of acceptability for the types of air quality.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/Aqichart.jpg)

https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/Aqichart.jpg

## Components 

This is a 0.96 inch blue OLED display module. The display module can be interfaced with any microcontroller using SPI/IIC protocols. It is having a resolution of 128x64. The package includes display board, display,4 pin male header pre-soldered to board.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/I2C-OLED-Display.jpg)

The MQ-135 gas sensor senses the gases like ammonia nitrogen, oxygen, alcohols, aromatic compounds, sulfide and smoke. The MQ-3 gas sensor has a lower conductivity to clean the air as a gas sensing material. In the atmosphere, we can find polluting gases, but the conductivity of the gas sensor increases as the concentration of polluting gas increases. MQ-135 gas sensor can be implemented to detect the smoke, benzene, steam and other harmful gases. It has the potential to detect different harmful gases. It is with low cost and particularly suitable for Air quality monitoring application.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/MQ135.png)

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/esp8266%20pinout.png)

## Assembly

Now let us assemble the hardware and do the coding for the great IoT project. We will interface MQ135 Air Quality Sensor with NodeMCU ESP8266 Board and 0.96″ I2C OLED Display. The circuit diagram is given below.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/MQ135-ESP8266.jpg)


 [Code Credit Mr.Alam](https://how2electronics.com/iot-air-quality-index-monitoring-esp8266/)