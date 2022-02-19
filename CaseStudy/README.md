# Case Study
1] Complex Embedded System
#Smart Helmet
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
 
 ## Block Diagram
 
 ![smarthelmet_blockDgm](https://user-images.githubusercontent.com/98841253/154783698-a52a98ee-1a16-42c8-af46-edc88868af00.JPG)
 
# Washing Machine

In a washing machine, the MCU gets analog inputs (water level sensor, water hardness sensor,water hardness sensor, humidity sensor, door open sensor, laundry load sensor, optical sensor, detergent density sensor, load Imbalance sensor, and volume sensor) through an external ADC. Temperature sensing is done by an onboard RTD and an external EEPROM is used to store data, such as customized wash program, memory backup, child lock, and favorites.  The microcontroller allows the washing machine to adjust the water and cut power automatically.

The MCU also controls self-diagnostics, including water supply failure, spin failure, drainage failure, child lock, overflow protection, and door lid open. Clocks and timers are used to implement sleep mode and add delays (delay start condition) in operations. A buzzer (PWM-based) generates tones at different frequencies and also provides alert tones during overload conditions. The MCU also automatically turns off the machine after washing is completed, thus saving power.

