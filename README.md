
# Description

A school project i'm sharing on github.

This project is a 2-part system to control OBS (a livestreaming/recording software):
+ An STM32 USB-HID based Controller.
+ A Python script, that works as a driver for the controller.

I made this as a request from my school's Robotics club. We record events frequently, and they wanted someone that could "improve and modernize the livestreams". So, along with creating graphics and resources for OBS, I also utilized my technical skills to create a controller for easy use and control. 
_________

## Electronics
The electronics includes a STM32 on a dev board (blackpill), and a self-made hat with a few buttons for control.

## Python Script (Driver)
A python script that utilizes OBS's webcontrol system. It stores values and translates button presses from the controller into various functions for complex control over OBS.
