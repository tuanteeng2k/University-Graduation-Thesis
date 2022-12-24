# University-Graduation-Thesis

# Design and manufacture self-driving car for service (Thesis)

# Suppervisor: Dr. Le Duy Tuan

# Author: K14-DHCDT

/******************************************************************************************/

/*********MAPPING********/

Tab1 - First: cd catkin_ws/src/turtlebot3_simulations/turtlebot3_gazebo/launch/

Tab2 - Second: cd catkin_ws/src/turtlebot3/turtlebot3_slam/launch/

Run 1: roslaunch turtlebot3_gazebo turtlebot3_world.launch

Run 2: roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping

RunTeleop: rosrun turtlebot3_teleop turtlebot3_teleop_key

/***********************/

rosrun map_server map_saver -f ~/map

/*******NAVIGATION....../

Tab1: roslaunch turtlebot3_gazebo turtlebot3_world.launch

Tab2: roslaunch turtlebot3_navigation turtlebot3_navigation.launch
