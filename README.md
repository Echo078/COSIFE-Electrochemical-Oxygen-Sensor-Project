# COSIFE-Electrochemical-Oxygen-Sensor-Project
This is a porject based on DFRobot Gravity I2C Oxygen Sensor and DHT22 Humidity Sensor. With the control of Elegoo uno R3 microcontroller, it could detect the real- time oxygen concentration, related humidity, and temperature. Since this system is expected to be applied in the laboratary portable glovebox, a passive buzzer, a LCD Display and a green LED are used as additional functions. During the operation, when the oxygen level decreases below a specific threshold, the alarm system will be initialized. Then once the threshold is passed, the passive buzzer will start alarming with the led begin fleshed. All the data will be displayed both on the serial monitor and the LCD screen. A 16GB micro SD card including all the user instructions is used to store the data in a spread csv. file.

This DFRobot Gravity I2C Oxygen Sensor works based on the principles of electrochemical oxygen sensor that using the chemical reaction of the electrodes and creating a flow of electrons between the anode and cathode. With high anti-interference ability, high stablility and high sensitivity, this arduino-compatible oxygen sensor can be widely applied to fields like portable device, air quality monitoring device, and industries. This sensor has an I2C output that it it can be calibrated in the air and compatible with many mainboards including Arduino Uno and Raspberry Pi. It supports input voltage 3.3v~5.5v and has an effective range 0~25% Vol. The lifespan is around 2 years.

# How to install
## Arduino Libraries
- <DHT.h>
- <LiquidCrystal.h>
- <SD.h>
- <SPI.h>
- [<DFRobot_OxygenSensor.h>](https://wiki.dfrobot.com/Gravity_I2C_Oxygen_Sensor_SKU_SEN0322#target_6)
## Instructions
1. Download [Arduino IDE](https://www.arduino.cc/en/software) in order to upload the code (please choose the right version depend on your operating system).
1. Install all above libraries by clicking `Sketch`-> `Include Library` -> `Manage Libraries`. Then typing in the full name of the library and choosing the latest version to install. 
1. For the [<DFRobot_OxygenSensor.h>](https://wiki.dfrobot.com/Gravity_I2C_Oxygen_Sensor_SKU_SEN0322#target_6), downloading the library as a zip file. Then clicking `Sketch`-> `Include Library` -> `Add ZIP. Library` and choosing the file name.
1. Click `Tools` to make sure `board` is connected to "arduino uno" and choose the right `port`.
1. Physically connect the usb cable to PC and upload the code (feel free to open the serial monitor on the top right conner to check data status)

