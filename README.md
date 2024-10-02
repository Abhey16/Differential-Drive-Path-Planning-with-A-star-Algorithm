# Differential-Drive-Path-Planning-with-A-star-Algorithm

## Node Exploration
---

https://github.com/Abhey16/Differential-Drive-Path-Planning-with-A-star-Algorithm/assets/132549463/be0e5ddd-768b-497a-bdec-750b580b09ca

## TurltleBot following the generated path
---

https://github.com/Abhey16/Differential-Drive-Path-Planning-with-A-star-Algorithm/assets/132549463/f359d49e-5b6a-4475-a941-37c633430f96

## Installation
---
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.
1. Create a directory with a subfolder named **src** on your local machine.
2. Navigate into the directory using Terminal and run:
```
colcon build
```
This will convert your directory into a ROS2 Workspace

3. Navigate to the src folder and clone the repository to your local machine:
```
https://github.com/Abhey16/Differential-Drive-Path-Planning-with-A-star-Algorithm.git
```
This will add ROS package in the **src** folder.

4. Navigate to the root of ROS2 directory and build the project using colcon:
```
colcon build
```
5. Source the environment to set up the necessary ROS2 variables:
```
source install/setup.bash
```
6. Now launch the Gazebo environment
```
ros2 launch turtlebot3_project3 competition_world.launch.py
```
7. Now run Planning and Navigation script:
```
ros2 run turtlebot3_project3 astar.py
```

