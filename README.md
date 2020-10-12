# Autopilot_V2
This is the Autopilot code for an UAV, running on a RTOS.


The following software was developed for to obtain the grade of Electronic and Control of Aircraft Systems Engineer at UNAQ. This software owns to **Ka'an Sat Team** 
from ```Universidad Aeronáutica en Querétaro (UNAQ)```. 
 The program runs on a the microcontroller ```TMS570LS04 of Texas Instruments``` using a Real Time Operating System
 based on FreeRTOS.

## Sensors:
Different sensors are used to control the lateral and longitudinal axis of the aircraft.
 * BMP280 (Pressure, Temperature, Altitude)
 * MPU9250 (Accelerometer, Gyroscope, Magnetometer)
 * GPS (Position)
 * Pitot Tube (Airspeed)

## Input PINS:
 ```
 GIO01
 etc. agregar pines de conexión
 ```
## Output PINS:
 ```
 GIO01 -> ADCetc
 etc. agregar pines de conexión
 ``` 

### Authors :
 * **Luis Ángel García Sánchez** - [4769@soyunaq.mx](4769@soyunaq.mx)
 * **Javier Jacal Juárez** - [@soyunaq.mx](@soyunaq.mx)
 
 ### Acknowledgments :
 * Hat tip to anyone whose code was used.
