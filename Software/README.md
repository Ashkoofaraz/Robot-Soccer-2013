 Soccer-Robot-2013 | Software
=================

## What is included here

### Libraries
Folder containing _almost_ all libraries used by projects. Others are contained in my [repositories](https://github.com/ivanseidel).

### SlaveKalman, Slave, SlaveIntensity, SlaveFast and SlaveRequest
Different, tested versions for the "Ball location" Firmware. The actually used is SlaveKalman, witch can filter and preddict even in noisy enviroments, where the ball is. This runs on the Atmega328, at 16Mhz.

### Soccer_v01 and Soccer_v02
Actual main code. Version 2 was the last one, and the final one as well.

Includes majority of funcion, interface to connect to external hardware. Operational System setup, robot setup, bluetooth management, Sensors and motors setup and checkup.

### Tests
Code that was kept to save time, and test specif purpouse tasks.
