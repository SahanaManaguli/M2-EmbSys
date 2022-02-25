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
|HLR4|The application should detect if any crashes|
|HLR5|The application should send SMS to the Vehicle Department/Police Station if drunken rider is detected|

## Low Level Requirements
 |ID  |DESCRIPTION                                                        |
 |:---|:------------------------------------------------------------------|
 |HLR1|Alcohol sensor continuously monitoring,if any drunken rider is detected the ignition should off and alarm will on|
 |HLR2|If helmet is not worned in that case also ignition should turned off|
 |HLR3|If any crashes happens it should send SMS to registered mobile|
 |HLR4|It should  indicate all the status of application on LCD and alarm|
 
 ## SWOT Analysis
 # Strengths
*Light Weight
*Cost Effective
 ## architecture

 
 ![smarthelmet_blockDgm](https://user-images.githubusercontent.com/98841253/154783698-a52a98ee-1a16-42c8-af46-edc88868af00.JPG)
 # System Design
 ## Components Required
 * ATMEGA328P Micro controller:
 * Alcohol Sensor
 * Vibration Sensor
 * Helmet switch
 * Motor
 * Motor driver
 * Relay
 * GPS
 * GSM
 * Alarm
 * LCD
 * Power Supply

