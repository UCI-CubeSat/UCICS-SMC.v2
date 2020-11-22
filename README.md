# UCI CubeSat OBC v2
### Made by UCI Avionics

These design files are for the System Management Controller and Communication Subsystem of the UCI CubeSat.  
They are NOT final and are subject to change and modifications.  

Verification and finalization pending.  

Features:
- STM32F412ZG microcontroller for SMC
- 2 STM32L431RCT6 microcontrollers for communications controllers
- RF MUX and CPLD switching logic for communications failover
- AX5043 communications transceiver over SPI bus
- TCAN1042 CAN transceiver
- 4 magnetorquer PWM outputs
- 2 BMX160 interial measurement units
- CPLD error detection and handling
- 12 sun sensor ADC ports
- System and magnetorquer current monitoring via INA226 shunt resistor I2C current sensors
- External application connector

