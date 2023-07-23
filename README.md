# RC Car Project
This repository contains all files for the controller boards I designed for a RC car I am building myself.

## Version 1
The first version of the board uses a AtMega 328 MCU for controlling the motor driver, lights, and steering of the car. It is connected to an external
ESP 8266 chip for enabling wireless communication.

<div align="center">
  <img src="https://github.com/P1NHE4D/rc-car/blob/master/images/v1_board_layout.png" width="33%" title="V1 Board Layout">
  <img src="https://github.com/P1NHE4D/rc-car/blob/master/images/v1_front.png" width="33%" title="V1 PCB Front">
  <img src="https://github.com/P1NHE4D/rc-car/blob/master/images/v1_back.png" width="33%" title="V1 PCB Back">
</div>



## Version 2
The second version is currently in development. It replaces the AtMega 328 chip with an on-board ESP32 in order to recude the overall footprint
of the chip. It also features a USB-C connector to facilitate flashing and debugging the controller without having to rely on additional 
debugging equipment.
