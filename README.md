# Physics-Simulating-Business-Card
 
The "Physics Simulating Business Card" is a electronic business card that runs on an STM32L412K8. The card contains an 8X8 LED matrix. The pixels in the matrix are individually addressable with a 74HC595 shift register controlling selecting rows and T2N7002 N-Channel MOSFETs controlling the columns. An MXC6655XA accelerometer is used to track orientation of the card which is used as input to a fluid simulation displayed on the LED matrix. This project is inspired by https://github.com/Nicholas-L-Johnson/flip-card.

![PCB Design](https://github.com/jberman3039/Physics-Simulating-Business-Card/blob/main/Images/Card.png)

# TODO

The firmware is currently in development. The STM32L412K8 will run CMSIS-RTOS for multi-threading tasks and will feature a custom driver for the MXC6655XA accelerometer. 
