# TFmini Lidar I2C

A C++ module for accessing the TFmini Lidar on a Raspberry pi 3b+. 


![Layout](https://github.com/TitiLouati/Cplusplus-Raspi-TFminiLidarI2C/blob/main/TFminirangefinderI2C/TfminiI2c.jpg)


# Example

Assuming that the  I2C slave address of your Tfmini Sensor is 0x10, you can read Lidar data from main.cpp like this: 

Distance = ... cm  strenth = ...    mode = ... 


# Dependecies

install G++ compiler by installing :  libc6-armel-cross libc6-dev-armel-cross binutils-arm-linux-gnueabi libncurses5-dev build-essential bison flex libssl-dev .

# Installation

To install these project follow those steps: 

```
git clone https://github.com/TitiLouati/Cplusplus-Raspi-TFminiLidarI2C.git

```
Then:


```
g++ -o main main.cpp tfmini.h tfmini.cpp gpio.cpp gpio.h

```



