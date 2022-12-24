# University-Graduation-Thesis

# Design and manufacture self-driving car for service (Thesis)

# Suppervisor: Dr. Le Duy Tuan

# Author: K14-DHCDT

/******************************************************************************************/

/*********MAPPING********/

Tab1: roslaunch turtlebot3_gazebo turtlebot3_world.launch

Tab2: roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping

Tab3 - RunTeleop: rosrun turtlebot3_teleop turtlebot3_teleop_key

/***********************/

rosrun map_server map_saver -f ~/map

/*******NAVIGATION....../

Tab1: roslaunch turtlebot3_gazebo turtlebot3_world.launch

Tab2: roslaunch turtlebot3_navigation turtlebot3_navigation.launch
