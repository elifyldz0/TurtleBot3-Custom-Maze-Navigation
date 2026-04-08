# 🤖 TurtleBot3 Custom Maze Navigation

This repository contains custom-designed environment maps and navigation configurations for **TurtleBot3** (Burger/Waffle) using **ROS 2 Humble**.

## 📍 Project Overview
In this project, I designed a custom maze environment to test autonomous navigation, SLAM, and path-finding algorithms. The goal was to create a challenging layout for the robot to navigate through using the **Nav2 stack**.

## 🛠 Tech Stack & Tools
- **Operating System:** Ubuntu 22.04 LTS
- **Middleware:** ROS 2 Humble
- **Simulation:** Gazebo / RViz2
- **Mapping:** SLAM Toolbox / Cartographer
- **Navigation:** Nav2 (Navigation 2)
- **Map Design:** GIMP (Custom .pgm editing)

## 📂 File Descriptions
- `maze2.yaml`: The configuration file containing map metadata.
- `maze2.pgm`: The occupancy grid map image representing the custom maze layout.
- `simple_map.yaml/pgm`: Initial testing maps used for basic localization verification.

## 🚀 How to Use
1. Clone this repository to your workspace:
   ```bash
   git clone [https://github.com/elifyldz0/TurtleBot3-Custom-Maze-Navigation.git](https://github.com/elifyldz0/TurtleBot3-Custom-Maze-Navigation.git)

   Launch your TurtleBot3 simulation with the custom map:
   ros2 launch nav2_bringup bringup_launch.py use_sim_time:=True map:=/path/to/maze2.yaml
  
