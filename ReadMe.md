# UR15 Robotics Arm

The aim of this project was to assemble the parts of the ur15 robot arm and visualise them in rviz which was done by creating a urdf file for the arm and setting the positions and motion type.

<img width="1392" alt="image" src="/UR15_1.png" />

## Steps to Launch the Arm

Ensure that you have the following already installed on your system
### 1. Prerequisites

install urdf tutorial
```
sudo apt install ros-humble-urdf-tutorial
```
Ubuntu<br>
ROS2 (humble was used for this project)<br>
Python3<br>
Others: git, rosdep

### 2. Steps to launch

Clone the repo
```
git clone (https://github.com/Iqmaa/UR15_arm_assembly.git)
```

Run the following commands line by line
```xml
colcon build --symlink-install
source install/setup.bash
ros2 launch urdf_tutorial display.launch.py model:=/home/iqma/Projects/Aurora_Arm_workshop/Task4_Iqma/src/arm_description/urdf/arm.urdf

```
## Expected Outcome

<img width="1392" alt="image" src="/UR15_2.png" />
