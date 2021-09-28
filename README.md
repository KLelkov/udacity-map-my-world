# udacity-mapmy-world
## Project 4: Map My World From Udacity Robotics Engeneer Nanodegree

### How to install
Simply put all three packages to the catkin_ws/src directory and run
```
catkin_make
```
from catkin_ws directory. This should build all the packages without problems!

### How to use
First you need to launch the world simulation with
```
roslaunch my_robot world.launch
```
Then you need to launch RTAB SLAM node with
```
roslaunch my_robot mapping.launch
```
And you're good to go!

You can run keyboard teleop node to control the robot manualy with
```
rosrun teleop_twist_keyboard teleop_twist_keyboard
```

### Map database
Can be found on googlde drive https://drive.google.com/file/d/1qmboehoJe7ap-ZPlH_KcBJF5xaLCP8Mm/view?usp=sharing

### Known Issues
#### Gazebo crash
Sometimes gazebo just crashes - simply relaunch it.
