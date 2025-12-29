# STMRocket (KiCad v9.0)

> An open source model rocket flight computer with datalogging & parachute deploying capabilities.
> 
<br>

<img width="400" height="800" alt="Screenshot 2025-12-28 230702" src="https://github.com/user-attachments/assets/bc445c4d-3088-4ec8-a8a5-a4b795fb9ef8" />
<img width="400" height="800" alt="Screenshot 2025-12-28 223825" src="https://github.com/user-attachments/assets/ac02665d-5fbc-4a91-ace0-98ec9161e885" />

<br>

## Project Description

This is a personal project for an STM32 flight computer that will be flown on a high-power rocket to achieve the Level 1 high power rocketry certification in Canada.

<br>


## Capabilities

The computer is able to store flight data from its two sensors:

- ICM42670: 6-axis IMU with a gyroscope and accelerometer
- BME280: Pressure, temperature and humidity sensor

Data from the accelerometer and gyroscope is used to activate the pyro charge and release the rocket's parachute (single-deploy configuration).

Flight data is stored in a 4-megabyte flash memory chip and is offloaded from the computer using MicroSD.

<br>

During flight, the computer is powered by a 2S LiPo battery through an XT30 connector.

Programming interfaces: SWD and USB Micro-B.

<br>

For a more detailed overview of the components, consult the BOM and the KiCad schematic.
