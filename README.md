# Turtle-Bot-Web-Control
ROS Web Control for Turtlebot3 
======================

## Installation
Firstly you must install turtlebot3, rosbridge server 
sudo apt-get install ros-melodic-turtlebot3
sudo apt-get install ros-melodic-rosbridge-server

```
then clone this repo

git clone https://github.com/NDNNhan123/Turtlebot-Ros-Web
```

## Usage with turtlebot3 simulation


export TURTLEBOT3_MODEL=burger
roslaunch turtlebot3_gazebo turtlebot3_world.launch
roslaunch rosbridge_server rosbridge_websocket.launch
roslaunch turtlebot3_navigation turtlebot3_navigation.launch
rosrun robot_pose_publisher robot_pose_publisher
```
then open index.html with your browser and control your robot.

I use a lot of javascript code which ones you can found in "rosjsScripts" directory are from robot web tools
http://robotwebtools.org/tools.html
