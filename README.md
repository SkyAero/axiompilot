
#  **Axiompilot**
![final11](https://user-images.githubusercontent.com/35519782/38603293-d3c344fe-3d8a-11e8-814f-a79f067d7050.png)


![nuttx](https://user-images.githubusercontent.com/35519782/38603308-d9a88820-3d8a-11e8-908d-1f80a5f3f407.png)






# **Development Roadmap (draft)**
## ESP8266
- Wifi telemetry and boot loading through ESP8266(config and firmware)
- MicroPython NuttX wrapper/connecter
- MavLink micropython library
- Wifi bridge for NuttX
- OTA update of STMF4
- Precompiled MicroPython libraries to make drone, rover and robots
- Extended  Micropython to stepper, DC and Servo motor controls 
- Extended  MicroPython to sensors
- Smartphone apps

## Hardware specifications

- Use 6 main PWM outputs to build quadcopter, hexcopter,rover and plane
- On board Invensense MPU9250 Accel / Gyro / Mag sensor
- Integrated Measurement Specialties MS5611 barometer sensor
- 8-bit Ardu Cam compatible Camera interface
- Supoorting ardu cam modules MT9V034,ov7670, ov2640, MT9v111, ov3640, ov5642
- On board 1G-bit of serial memory.
- 4 Mbit NV ram replaced with 128K bit  F-ram memory.
- On board GPS with chip antenna.
- TJA1051 as CAN transreceiver
- On board Multicolor LED for visual indicator
- Buzzer for audio indicator


## Port Mapping

| Function       | Pins           | Connector  |
| ------------- | ------------- |------------- |
| PWM1          | 3             | Header       |
| PWM2  | 3  | Header|
| PWM3  | 3  | Header  |
| PWM4  | 3  | Header |
| PWM5  | 3  | Header |
| PWM6  | 3  | Header     |
| SPI  | 7  | Header        |
| I2C  | 4| Header     |
| UART  | 3  | Header        |
| SBUS  | 3  | Header      |
| CAMERA CONNECTOR |  17 | Header|
|VBAT|3|Header|
| TELEMETRY  | 6  | JST-GH     |
| CAN  | 4| JST-GH          |
| JTAG  | 6  | JST-GH            |
| USB | 4  | usb connector|

**Useful resources** : pixhawk, NuttX, pixracer, micropython port of esp8266, dronecode.org and dronekit, if any design is not attributed please mail us @ ![contact](https://user-images.githubusercontent.com/35519782/38604037-deefac1c-3d8c-11e8-83f3-6787e44e152e.png)



