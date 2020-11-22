

This is just an **overview**. Details will be developed in other pages


# Processor block
* Typically based on a microcontroller
* Is responsible for “slow” tasks and tasks with high memory size requirements
* Examples:  
Sends speed requirement to the logic block  
Monitor all temperatures  
Data logging


# Logic block
* Typically based on a FPGA
* Is responsible for “medium speed” functions
* Examples:  
Motor control (e.g. Field-Oriented Control)  
Phase over current detection

# Driver block
* Driver for the Power block (i.e. MOSFET/IGBT gate driver)
* Electrical insulation between the Logic block (LV = low voltage side) and the Power block (HV = high voltage side)
* Is responsible for “fast” functions
* Examples:  
Power semiconductor overcurrent protection (“DESAT” protection)  
Dead time generation

* Is responsible for all HV side measurements
* Examples:  
Phase currents  
DC voltage  
Phase voltages (sensorless mode only when no switching ????)

# Power block
Typically consists in:
* Power semiconductors (e.g. MOSFET or IGBT) in half bridge configuration
* Capacitor(s) to filter/stabilize the DC power

