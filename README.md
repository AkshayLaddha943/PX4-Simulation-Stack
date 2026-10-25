# PX4-Simulation-Stack
This repository provides the steps to configure a drone model with downward facing camera and an IMU to evaluate a visual-inertial system for navigation

## Setup

### Gazebo World & Drone Model

For this use case, we will use the baylands world from PX4 development environment, due to its diverse and feature-rich environment. The drone is configured with a downward-facing camera and an IMU and is later evaluated against the ground truth position from Gazebo, essential for evaluating our navigation system's accuracy.

Run the command:



### QGC
QGroundControl is the GCS allowing us to set waypoints, mission plan and monitor drone health during flight. 

Run the command:

### Sensor Data
There are two ways to receive sensor data

#### Gazebo -> ROS2

#### Using uXRCE-DDS (PX4-ROS 2/DDS Bridge)


### Visualize the sensor data
In order to visualize the sensor data, we will use the Rviz2 visualization tool

