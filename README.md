# RoboND_Go_chase_it
Design and build a mobile robot, and house it in a world. Then programm the robot with C++ node in ROS to chase white colored ball.
## Prerequisites
 1. Gazebo and ROS on Linux
 2. Cmake and gcc/g++ 
## Usages
 1. Clone and initialize project with a catkin workspace
```
$ mkdir catkin_ws && cd catkin_ws
$ git clone https://github.com/fehlen501602/RoboND_Go_chase_it.git
$ mv RoboND_Go_chase_it src
$ cd src && catkin_init_workspace
``` 
 2. Build
```
$ cd ..
$ catkin_make
```
 3. Launch the world
```
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```
 4. Launch the ball_chaser package in another terminal
```
$ source devel/setup.bash
$ roslaunch ball_chaser ball_chaser.launch
```
Place the white ball in front of the mobile robot. The robot will follow the ball.
