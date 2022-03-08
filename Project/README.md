# Smart Helmet
## Abstract
Now a days bike accidents are happening more due to drunken driving in that case if the rider not worn the helmet that leads to death.considering all this issues
The Smart Helmet application is implementing to detect whether the rider is drunken or not and it ensures the helmet is worn or not.If these conditions falls the bike ignition system should turn off and it will detect if any crashes happens.The GSM sends SMS to registered vehicle department/Police station for further actions.

 
 # System Design
 ## Components Required
 ##ATMEGA328P Micro controller:
 In this project, microcontroller ATMEGA 328p is used.It can be known as brain of this 
circuit.. One can store commands and values which occur during the mechanism of circuit. 
All the signals are processed in microcontroller and send it to various other devices.
 
 ## Alcohol Sensor(Mq-3)
 This sensor is used to detect alcohol content in biker’s breath. It runs on voltage supply of 2-
3.3V. If the sensitivity of MQ-3 is more than 0.04mg/L in breathe then the driver can't drive 
the bike
 
 ## Helmet switch
 The switch is used to check the helmet is worn or not
 ##Motor
 In this project the motor is used as bike ,if all the conditions satisfied the motor will on otherwise off.
 ## Stepper Motor
 In this project the stepper motor acts as bike,When the helmet is worn the motor will starts to rotate. If the helmet is removed or alcohol is detected the motor will off.It means ignition system of bike will turn off.
## Buzzer
Buzzer is used as actuator when the alcohol is detected the buzzer starts to buzz.
## LED
LED is used for indication of alcohol detection if the rider is drunken the LED will ON along with buzzer.

 ## LCD
 The status of the system is displayed on LCD
 ## Power Supply
 This is required for controller.
 ## Code Analysis
 |Codacy|Codiga Grade|codiga Marks|cpp-check|
|:-----|:-----|:---------|:----------------|
|[![Codacy Badge](https://app.codacy.com/project/badge/Grade/ef1109668c6c4f9d8f97c934d205cee9)](https://www.codacy.com/gh/SahanaManaguli/M2-EmbSys/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=SahanaManaguli/M2-EmbSys&amp;utm_campaign=Badge_Grade)      | ![Codiga Badge](https://api.codiga.io/project/31629/status/svg)|![Codiga Badge](https://api.codiga.io/project/31629/score/svg)|  |

