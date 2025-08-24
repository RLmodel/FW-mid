# FW-01
YUHESEN FW-01 Omnidirectional UGV ROS2 driver

# ROS2 Packages for Yuhesen FW-01 Mobile Robot
https://www.youtube.com/watch?v=qx_waTaB-XQ&t=16s

## Packages

This repository contains minimal packages to control the FW-01 robot using ROS. 


* yhs_can_control: a ROS wrapper around to monitor and control the fw-01 robot
* yhs_can_interfaces: fw-01 related message definitions

## Supported Hardware

* fw-01

## Basic usage of the ROS packages

1. Clone the packages into your colcon workspace and compile


    ```
    $ sudo apt-get update
    $ sudo apt-get install build-essential git cmake libasio-dev
    $ git clone https://github.com/RLmodel/FW-01.git
    ```

![Image](https://github.com/user-attachments/assets/f437131d-fad8-4782-ade7-1eaf4fae4a51)
