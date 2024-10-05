# ROS Mobile Robot Simulation

This repository contains the ROS2-based mobile robot simulation using Gazebo. The project includes the URDF model of a 4-wheeled robot, navigation parameters, and launch files for running the simulation.

## Features
- Mobile robot simulation in Gazebo
- URDF model of the robot
- Configurable navigation parameters (nav2)
- Gazebo launch file

## Prerequisites
Before using the repository, ensure you have the following installed:
- ROS2 (Humble/other ROS2 distribution)
- Gazebo
- ROS2 Navigation2 stack

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd ws_mobile (copy)
   ```

2. Build the package:
   ```bash
   colcon build
   ```

3. Source the workspace:
   ```bash
   source install/setup.bash
   ```

## How to Run
Launch the Gazebo simulation:
```bash
ros2 launch mobile_robot gazebo_model.launch.py
```

## File Structure
- `src/mobile_robot/model/robot.xacro`: URDF model of the mobile robot.
- `src/mobile_robot/launch/gazebo_model.launch.py`: Launch file for the Gazebo simulation.
- `src/mobile_robot/param/nav2_params.yaml`: Navigation2 parameters for the robot.



