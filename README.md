# ROS SoI-2025  
**ROS2 4-Wheeled Differential Drive Robot Simulation**

## System Info
- **Host OS**: Windows  
- **Guest OS**: Ubuntu 22.04.5 LTS (running inside Oracle VirtualBox)  
- **ROS 2 Version**: Iron Irwini  
- **Gazebo Version**: 11.10.2  
- **Note**: Running ROS and Gazebo inside a Virtual Machine - GUI performance may be limited due to VM graphics support.

## Issue
Gazebo is installed but the GUI does not launch.  
Tried launching via both `gazebo` and `ros2 launch`, but nothing happens.

## Setup Instructions

Before launching anything, make sure to source ROS 2 Iron in every new terminal:

```bash
source /opt/ros/iron/setup.bash

## How to Launch

1. Build your workspace:
   ```bash
   colcon build
   source install/setup.bash
