# Smart Helmet
## Abstract
Now a days bike accidents are happening more due to drunken driving in that case if the rider not worn the helmet that leads to death.considering all this issues
The Smart Helmet application is implementing to detect whether the rider is drunken or not and it ensures the helmet is worn or not.If these conditions falls the bike ignition system should turn off and it will detect if any crashes happens.The GSM sends SMS to registered vehicle department/Police station for further actions.
# Requirements
## High Level Requirements
|ID  |DESCRIPTION                                                        |
|:---|:------------------------------------------------------------------|
|HLR1|The Application should detect the alcohol|
|HLR2|The Application should check whether the helmet is worn or not|
|HLR3|If any above case failed the system should off the ignition system of bike|
|HLR4|The Buzzer will ON if alcohol detected|
|HLR5|The LED will ON and status is updated on LCD|

## Low Level Requirements
 |ID  |DESCRIPTION                                                        |
 |:---|:------------------------------------------------------------------|
 |LLR1|System will check for helmet switch|
 |LLR2|If helmet is not worn display message on LCD "No Helmet"|
 |LLR3|The Ignition system will ON |
 |LLR4|If alcohol detected Buzzer and LED will ON|
 |LLR5|It should  indicate all the status of application on LCD |
 
 # SWOT Analysis
 ## Strengths
 * Light Weight
 * Cost Effective
 * Environment Freindly
 * Better mechanical properties
 ## Weakness
 * Hand layout process
 * Low density
 ## Opportunities
 * Vast use of natural fiber
 * Design can be updated easily
 ## Threads
 * If the ratio of resin and hardner can't use properly the mechanical proprties can be changed rather than expected
 # 4W'S & 1H
 ## WHO
 The smart helmet is an system. It can be used by all bike riders.
 ## WHAT
 Smart Helmet is an safety system for bike riders and it will reduce the drunken drivers.
 ## WHEN
 This smart helmet is very useful for both bike riders and traffic police system when rider may drunken and not wearing the helmet.
 ## Where
 The smart helmet is essential for all bike riders and can be used in hazardous manufacturing area.
 ## How
 The smart helmet will detect alcohol,crashes etc

 

 ## architecture
 # Structural Diagram

 
 ![smarthelmet_blockDgm](https://user-images.githubusercontent.com/98841253/154783698-a52a98ee-1a16-42c8-af46-edc88868af00.JPG)
 # Behavioral Diagram
 ![behave_smart helmet](https://user-images.githubusercontent.com/98841253/155775666-4061d581-0556-47e0-aaec-68b28bcb6749.JPG)

 
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
 ## Vibration Sensor
 Vibration sensors are sensors for measuring, display, and analyzing linear velocity, 
displacement and proximity or acceleration.
 ## Helmet switch
 The switch is used to check the helmet is worn or not
 ##Motor
 In this project the motor is used as bike ,if all the conditions satisfied the motor will on otherwise off.
 ## Motor driver
 A driver is used to connect micro controller and motor
 ## Relay
 Relay is used in between the GSM/GPS and controller
 ## GPS
 The Global Positioning System (GPS) is a satellite-based navigation system which is used to 
detect the location where the accident will be taken place. It detects the Longitude and 
Latitude values of particular place and sends it to GSM module.

 ## GSM
 GSM abbreviates as Global System for Mobile communication. It is used to establish 
connection between a computer and GSM system. It includes standard interfaces like RS232, 
USB, etc.. It is used to send messages through the SIM.
 #3 Alarm
 The alarm will ON if the helmet is not worn,alcohol detected and any accident happens
 ## LCD
 The status of the system is displayed on LCD
 ## Power Supply
 This is required for controller.
 ## Code Analysis
 |Codacy|Codiga Grade|codiga Marks|cpp-check|
|:-----|:-----|:---------|:----------------|
|      | ![Codiga Badge](https://api.codiga.io/project/31629/status/svg)|![Codiga Badge](https://api.codiga.io/project/31629/score/svg)|  |

