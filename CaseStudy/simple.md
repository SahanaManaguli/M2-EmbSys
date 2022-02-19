## Washing Machine
In a washing machine, the MCU gets analog inputs (water level sensor, water hardness sensor,water hardness sensor, humidity sensor, door open sensor, laundry load sensor, optical sensor, detergent density sensor, load Imbalance sensor, and volume sensor) through an external ADC. Temperature sensing is done by an onboard RTD and an external EEPROM is used to store data, such as customized wash program, memory backup, child lock, and favorites.  The microcontroller allows the washing machine to adjust the water and cut power automatically.

The MCU also controls self-diagnostics, including water supply failure, spin failure, drainage failure, child lock, overflow protection, and door lid open. Clocks and timers are used to implement sleep mode and add delays (delay start condition) in operations. A buzzer (PWM-based) generates tones at different frequencies and also provides alert tones during overload conditions. The MCU also automatically turns off the machine after washing is completed, thus saving power.
![block_dgm](https://user-images.githubusercontent.com/98841253/154610400-734c6ce5-850e-4f0b-a284-39aff16a6ef2.jpg)
## Design/Working
* The washing machine uses 8-, 16-, and 32-bit microcontroller-based circuitry for motor control and TRIAC/ LED/ LCD drive applications. 
* The MCU controls and manages all the functions and feature of the appliance. 
* When the user presses the start button, the input goes to the microcontroller from the front panel keyboard and the MPU starts the three-phase brushless DC (BLDC) motor/permanent magnet synchronous motor (PMSM). Motor speed will be varied and controlled as per user inputs from the front panel keypad.
* The MCU uses either an internal or external serial EEPROM (I2C/SPI based) to store old data. 
* It uses a real-time clock (RTC) for displaying accurate time information. 
* Temperature measurements are done using an onboard resistance temperature detector (RTD)-, thermistor-, or thermocouple-based temperature sensing device.
* The MCU uses an external ADC and amplifiers for receiving analog inputs from sensors, temperature, and battery. It uses external signal conditioning, comparators, and gate     driver circuitry for driving and controlling a 3-phase BLDC/ PMSM motor. The microcontroller can also receive remote control inputs through an IR receiver (at 38 kHz input).
* External buffer driver circuitry is required to drive 7-segment LED/LCD/graphical displays. Typically a 7-segment LED/LCD/graphical display with backlight is used for showing temperature, battery input, speed value, and error/warning messages. The microcontroller also interfaces with onboard peripherals such as I2C/ SPI and external peripherals like UART/USB communications.
