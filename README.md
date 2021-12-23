# MAV hardware- and software-setup

#### [Paper](https://doi.org/10.3929/ethz-b-000520507) | [Video](https://www.youtube.com/watch?v=ytru7-iqqB4) | [Wiki](https://github.com/VIS4ROB-lab/mav_hardware/wiki)

This repository contains a description of the harware- and software-setup used at the Vision for Robotics Lab for autonomous MAV flights, see Figure 1.

Please head over to the [wiki](https://github.com/VIS4ROB-lab/mav_hardware/wiki) of this repository for the full description.

![MAV](https://user-images.githubusercontent.com/36622275/144840501-4bebdb8a-6e13-42ce-907e-f93119899951.jpg)
**Figure 1** MAV during fully autonomous flight.

### Content
[**MAV Hardware**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware)  
    [**Frame**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#frame)  
    [**On-Board Computing**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#on-board-computing)  
        [Communication with the Flight Controller](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#communication-with-the-flight-controller)  
        [Intel NUC](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#intel-nuc)  
        [Jetson](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#jetson)  
        [Example Setup](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#example-setup)  
    [**Remote Control**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#remote-control)  
    [**Power**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#power)  
        [Batteries](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#batteries)  
        [Power Hot-Swap](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#power-hot-swap)  
        [12V Rail](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#12v-rail)  
        [Wiring](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#wiring)  
    [**Sensors**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#sensors)  
    [**Resources**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#resources)  
        [3D Modelled Parts](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#3d-modelled-parts)  
        [PCBs](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Hardware#pcbs)  
[**MAV Software**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software)  
    [**Overview**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#overview)  
    [**Mavros**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#mavros)  
    [**QGroundControl**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#qgroundcontrol)  
    [**Planning with ROS**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#planning-with-ros)  
        [Using RTK GPS](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#using-rtk-gps)  
        [Using Visual-Inertial Odometry](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#using-visual-inertial-odometry)  
        [Sending commands to the MAV](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#sending-commands-to-the-mav)  
    [**Useful Software**](https://github.com/VIS4ROB-lab/mav_hardware/wiki/MAV-Software#useful-software)  


### Publication

This work was presented at the _9<sup>th</sup> International Conference on 3D Vision (3DV 2021)_ in the demo session. 
If you use this repository in your academic work, please cite ([PDF](https://doi.org/10.3929/ethz-b-000520507)):

    @misc{Kompis2021Fully,
      copyright = {In Copyright - Non-Commercial Use Permitted},
      year = {2021-12-02},
      author = {Kompis, Yves and Bartolomei, Luca and Chli, Margarita},
      DOI = {10.3929/ethz-b-000520507},
      title = {Fully Autonomous Live 3D Reconstruction with an MAV: Hardware- and Software-Setup},
      Note = {9th International Conference on 3D Vision (3DV 2021); Conference Location: Online; Conference Date: December 1-3, 2021; This demo was presented at the International Conference on 3D Vision (3DV) 2021}
    }

### Abstract
_In this demo we present a versatile Micro-Aerial Vehicle (MAV) setup demonstrating fully autonomous live 3D reconstruction in real-world scenarios. With the aim of reproducability we provide key information on both the hardware- and software-setup._

### Video
**Fully Autonomous Live 3D Reconstruction with an MAV: Hardware- and Software-Setup** 1:56
[![Video](https://img.youtube.com/vi/ytru7-iqqB4/0.jpg)](https://www.youtube.com/watch?v=ytru7-iqqB4) 

