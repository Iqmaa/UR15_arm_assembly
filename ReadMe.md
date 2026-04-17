## UR15 Robotics Arm

The aim of this project was to assemble the pats of the ur15 robot arm and visualise them in rviz which was done by creating a urdf file for the arm and setting the positions and motion type.

<img width="1392" alt="image" src=" " />

### Launch the Arm

Ensure that you have the following alreasy installed on your system
#### Prerequisites

Ubuntu
ROS2 (humble was used for this project)
Python3
Others: git, rosdep

#### Steps to launch

Clone the repo
```
git clone (insert link)
```

Ru the following commands line by line
```xml
colcon build --symlink-install
source install/setup.bash
ros2 launch urdf_tutorial display.launch.py model:=/home/iqma/Projects/Aurora_Arm_workshop/Task4_Iqma/src/arm_description/urdf/arm.urdf

```

youre supposed to push only the things in source? (check how to properly push a ros2 packagae so  its easy for people to install)