# gazebo-pioneer-leaderfollower
ROS–Gazebo simulation for Pioneer 3-DX UGVs in leader–follower collaboration. The leader follows a square trajectory with event-driven rotations, while the follower uses adaptive control and state-based behaviors (pause, gap closing, yaw alignment). MQTT ensures robust, real-time inter-robot coordination.


## 📄 Setup Guide

This repository includes a detailed setup guide for running the **Pioneer 3DX leader–follower simulation in ROS Noetic**.  
You can:

- [Read the PDF version here](doc/p3dx_setup_guide.pdf)  

### Quick Start (from the guide)
1. Clone the Pioneer 3DX package:
   ```bash
   cd ~/catkin_ws/src
   git clone https://github.com/NKU-MobFly-Robotics/p3dx.git

2. Install dependencies:
   sudo apt install ros-noetic-gazebo-ros ros-noetic-gazebo-ros-control \
    ros-noetic-diff-drive-controller ros-noetic-joint-state-controller \
    ros-noetic-robot-state-publisher python3-rosdep python3-catkin-tools
3. Build your workspace:
   cd ~/catkin_ws
    catkin build
    source devel/setup.bash
   
