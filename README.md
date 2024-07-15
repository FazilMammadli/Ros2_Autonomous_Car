# ROS2 Autonomous Car


## Overview

This project focused on developing an autonomous vehicle using ROS2 and OpenCV. The project integrates various components such as lane detection, object tracking, and AI-based sign classification to create a comprehensive autonomous driving system.

### Features

- **Lane Detection:** Using computer vision techniques to detect and follow lanes.
- **Traffic Light Detection:** Identifying and reacting to traffic lights.
- **Sign Classification:** Utilizing a custom-built Convolutional Neural Network (CNN) to classify road signs.
- **Object Tracking:** Real-time tracking of objects using OpenCV.
- **Simulation Environment:** A simulated environment using Gazebo to test and validate the autonomous driving algorithms.

## Installation

### Prerequisites

Ensure you have the following software installed:

- **Ubuntu 20.04 (LTS)**
- **ROS2 Foxy Fitzroy**
- **Python 3.8**
- **OpenCV 4.2**
- **TensorFlow 2.14**

### Usage

1. **Launch the Gazebo Simulation:**

   ```sh
   ros2 launch self_driving_car_pkg world_gazebo.launch.py



2. **Run the Autonomous Node:**

   ```sh
   ros2 run self_driving_car_pkg computer_vision_node



## Results
* **Car**
  -  ![alt text](https://github.com/FazilMammadli/Ros2_Autonomous_Car/blob/master/results/the_car.gif)
    
* **Traffic Lights Detection and Related Motion**
  -  ![alt text](https://github.com/FazilMammadli/Ros2_Autonomous_Car/blob/master/results/trafficlight.gif)
 
 
* **Road Sign Detection**
  -  ![alt text](https://github.com/FazilMammadli/Ros2_Autonomous_Car/blob/master/results/sign.gif)

* **Lane Detection**
  -  ![alt text](https://github.com/FazilMammadli/Ros2_Autonomous_Car/blob/master/results/lane_detection.gif)
