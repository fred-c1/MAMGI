
# 1-Measurements
## V_HVDC = HVDC_P - HVDC_N
## Phase voltages:
V_A = PHASE_A - HVDC_N  
V_B = PHASE_B - HVDC_N  
V_C = PHASE_V - HVDC_N

## Phase currents:
sign convention = TBD  
I_A, I_B and I_C

## Temperatures
isolated measurments  
non isolated measurements


# 2-Gate drivers


# 3-Fault detection
Each fault is provide with an individual active Low logic signal to the logic block  
Faults are not latched in the driver block but in the logic block

## the following faults are not detected in the driver block
They are detected (digitaly) in the logic block  
V_HVDC overvoltage  
I_A, I_B and I_C overcurrents


