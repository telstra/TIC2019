# TIC2019
Everything you need to get started on the 2019 Telstra Innovation Challenge


## What's in the University Kit?

In your university welcome pack, you should have;
- 1x Arduino MKR NB 1500
- 1x Adafruit Ultimate GPS board 
- 1x GPS antenna
- 1x Temperature and Humidity Sensor
- 1x Gyroscope and Accelerometer board
- 1x Telstra Sim Card
- 1x Micro-USB Cable
- Several Header Connectors (Male-Female) 


## Setting up your Arduino

1. Download the [Arduino IDE](arduino.cc)
2. Install the libraries for the Arduino MKR NB 1500
 1. Open the Arduino boards manager

 ![arduino-boards-manager-menu]

 2. Search for "MKR" and install the libraries for the MKR NB 1500

 ![arduino-boards-manager-window]

 3. Select "Arduino MKR NB 1500" from the boards menu.
 
 ![arduino-select-nb1500]

3. Connect your Arduino to your computer
4. Put your SIM card in the Arduino
5. Test your board using the _Test Modem_ sketch under File > Examples > MKRNB > Tools


### Using the GPS module

[See Adafruit's guide for using the GPS module](https://learn.adafruit.com/adafruit-ultimate-gps/arduino-wiring)


### Using the temperature and humidity sensor

[See Adafruit's guide for using the temeperature and humidity sensor](https://learn.adafruit.com/dht/using-a-dhtxx-sensor)

Note that you have been supplied a *DHT11* temperature and humitidy sensor.


### Using the gyroscope and accelerometer board

[See this guide for using the gyroscope and accelerometer board](https://electrosome.com/interfacing-mpu-6050-gy-521-arduino-uno/)


## Connect your Arduino to Microsoft Azure IoT

[See this guide for connecting your Arduino to Microsoft Azure IoT](https://github.com/telstra/TIC2019-Azure-Guide)



[arduino-boards-manager-menu]: images/arduino-boards-manager-menu.png "Open the boards manager window"
[arduino-boards-manager-window]: images/arduino-boards-manager-window.png "Download the libraries for the MKR NB1500"
[arduino-select-nb1500]: images/arduino-select-nb1500.png "Select the MKR NB 1500 board"