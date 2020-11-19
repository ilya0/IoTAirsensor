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

ESP32 is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and dual-mode Bluetooth. The ESP32 series employs a Tensilica Xtensa LX6 microprocessor in both dual-core and single-core variations and includes built-in antenna switches, RF balun, power amplifier, low-noise receive amplifier, filters, and power-management modules. ESP32 is created and developed by Espressif Systems, a Shanghai-based Chinese company, and is manufactured by TSMC using their 40 nm process.[2] It is a successor to the ESP8266 microcontroller.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/esp8266%20pinout.png)

## Assembly

Now let us assemble the hardware and do the coding for the great IoT project. We will interface MQ135 Air Quality Sensor with NodeMCU ESP8266 Board and 0.96″ I2C OLED Display. The circuit diagram is given below.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/MQ135-ESP8266.jpg)

## Setting up Thingspeak

ThingSpeak is an open-source Internet of Things application and API to store and retrieve data from things using the HTTP and MQTT protocol over the Internet or via a Local Area Network. Thingspeak enables you to collect, store, analyze, visualize, and act on data from sensors.

To setup the Thingspeak Server, visit https://thingspeak.com/. Create an account or simply sign in if you created the account earlier. Then create a new channel.

![](https://github.com/ilya0/IoTAirsensor/blob/master/Wiring%20images/thingspeak.jpg)

 [Code Credit Mr.Alam](https://how2electronics.com/iot-air-quality-index-monitoring-esp8266/)
 
## Programming ESP32

Programming of the esp32 is a relatively simple affair, although requires proper setup. Although too long to go into details here, this link will go into depth about how to get the Arduino software IDE setup

 [Setting up the Arduino IDE](https://circuitdigest.com/microcontroller-projects/programming-esp32-with-arduino-ide)
 
 
## Credits


 [Project Credits go to Mr.Alam ](https://how2electronics.com/iot-air-quality-index-monitoring-esp8266/)