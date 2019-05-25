# TIC2019
Everything you need to get started on the 2019 Telstra Innovation Challenge


## What's in the Innovation Challenge Kit?

In your welcome pack, you should have;
- 1x Arduino MKR NB 1500
- 1x Arduino MKR ENV Shield
- 1x Adafruit Ultimate GPS board 
- 1x Telstra Sim Card
- 1x Micro-USB Cable
- Several Header Connectors (Male-Female) 
- (Optional) 1x $100 Microsoft Azure Pass


## Setting up your Arduino

1. Download the [Arduino IDE](arduino.cc)
1. Install the Arduino MKR NB 1500 board;
    1. Open the Arduino boards manager  
    ![arduino-boards-manager-menu]
    1. Search for "MKR" and install the libraries for the MKR NB 1500  
    ![arduino-boards-manager-window]
    1. Select "Arduino MKR NB 1500" from the boards menu.  
    ![arduino-select-nb1500]
1. Connect your Arduino MKR NB 1500 to your computer
1. Put your SIM card in the Arduino
1. Test your board using the _Test Modem_ sketch under File > Examples > MKRNB > Tools


### Using the Arduino MKR ENV Shield

[See Arduino's guide for using the MKR ENV shield](https://www.arduino.cc/en/Guide/MKRENVShield)


### Using the GPS module

[See Adafruit's guide for using the GPS module](https://learn.adafruit.com/adafruit-ultimate-gps/arduino-wiring)


## Connecting your Arduino to Microsoft Azure IoT

[Redeem your Microsoft Azure pass](https://www.microsoftazurepass.com/)

[See this guide to connect your Arduino to Microsoft Azure IoT](https://github.com/telstra/TIC2019-Azure-Guide)



[arduino-boards-manager-menu]: images/arduino-boards-manager-menu.png "Open the boards manager window"
[arduino-boards-manager-window]: images/arduino-boards-manager-window.png "Download the libraries for the MKR NB1500"
[arduino-select-nb1500]: images/arduino-select-nb1500.png "Select the MKR NB 1500 board"
