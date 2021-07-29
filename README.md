# Emb_C_LTTS
## CI and Code Qaulity
|Build|CppCheck|Codacy|
|:--:|:--:|:--:|
[![Compile-Linux](https://github.com/Yogendraman/Emb_C_LTT/actions/workflows/complie.yml/badge.svg)](https://github.com/Yogendraman/Emb_C_LTT/actions/workflows/complie.yml)|[![Cppcheck](https://github.com/Yogendraman/Emb_C_LTT/actions/workflows/cpp.yml/badge.svg)](https://github.com/Yogendraman/Emb_C_LTT/actions/workflows/cpp.yml)|[![Codacy Badge](https://api.codacy.com/project/badge/Grade/eb23952f20cc4cabb50371d4ac6f0247)](https://app.codacy.com/gh/Yogendraman/Emb_C_LTT?utm_source=github.com&utm_medium=referral&utm_content=Yogendraman/Emb_C_LTT&utm_campaign=Badge_Grade_Settings)|



Embedded Training LTTS
# Embedded C Case Study
Seat Heating System
-----------------
# Problem Statement: 
![activity_list](https://github.com/Yogendraman/Emb_C_LTTS/blob/main/Simulation/activity_list.png)
1. Button Sensor will check the passenger is sited or not
2. Temperature sensor works as :

ADC Value (Temp Sensor)| Output PWM
----------|----------
0-200 | 20% - 20 °C
210-500 | 40% - 25 °C
510-700 | 70% - 29 °C
710-1024 | 95% - 33 °C

3. Display CDD- CRO will give the temperature value by 
showing PWM.
4. Led Actuator shows the driver is sited 
5. Heater will check the heater button is ON.
6. Temp to CAN shows the value of temperature gone 
over protocol
## In Action

|OFF|
|:--:|
|![OFF](Simulation/activity4-off.PNG)|
|On|
|![ON](Simulation/activity4-on.PNG)|
