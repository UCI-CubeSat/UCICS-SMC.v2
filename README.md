# UCI CubeSat ADCS
### Made by Elijah Reed

These design files are for the System Management Controller and Communication Subsystem of the UCI CubeSat.  
They are NOT final and are subject to change and modifications.  TI parts have primarily been used.  

Verification and finalization pending.  

Features:
- TI TMS320F28386DZWTQ dual-core C28x microcontroller + Arm Cortex M4 + FPU64
- 512Mb 143MHz DRAM
- 3Gb NAND flash (1Gb x 3 split among SMC core, Comms 1, and Comms 2)
- CAN bus interconnect with TCAN1042 transceivers with 5V CAN logic level
- System current monitoring and maqnetorquer drive core current monitoring
- Magnetorquer PWM gate drivers controlled via SMC core
- Xilinx XC9572XL-10VQG44C CPLD for fault detection and handling
- Dual BMX160 IMUs and dual TMP100 board mount temperature sensors
- Dual TI TM4C1230D5PMI7R Arm Cortex M4F microcontroller for communications subsystem
- Dual CC1200 Sub-GHz 868-915 MHz transceivers with antenna RF switch for single antenna operation (for handing control to operational communication unit in case of comms fault)
- SMA antenna with 50Z drive strength
- 4 independent JTAG ports for 4-way simultaneous connections and cost savings
- 5V input with 3.3V 97.5% efficient DC-DC converter onboard
- Application connector for external interfacing