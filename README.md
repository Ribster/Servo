# Servo
This project is all about accuratly driving brushless motors, for cheap. The aim is to make it possible to use inexpensive brushless motors in high performance robotics projects.
Like this:
[![Servo motor control demo](https://j.gifs.com/lYx7k6.gif)](https://www.youtube.com/watch?v=WT4E5nb3KtY)

This repository used to contain all the development, but I decided to split it up into many different repositories.
* [ODriveFirmware](https://github.com/madcowswe/ODriveFirmware): Firmware that runs on the board.
* [ODrive](https://github.com/madcowswe/ODrive): Configuration and analysis scripts that runs on a PC.
* [ODriveHardware](https://github.com/madcowswe/ODriveHardware): Circuit board design

There is also [ODriveFPGA](https://github.com/madcowswe/ODriveFPGA), which contains the FPGA logic and software that runs on the FPGA based ODrive. This is not currently in development, but may be resumed at some later date.
