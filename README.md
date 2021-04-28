# Abstract
This is the sample code based on the turtlebot3-burger. This code active the node "sample" and the other sensor nodes. When running this code, terminal would show the laser angel and range data. You can use it easily by modifying the function at 'turtlebot3_sample/src/sample.cpp'.

# About us
* Date:2021/4/27
* Developer: Hsin, Jhao 
  * Contact:94332eric@gmail.com

# Compile the code
$ cd ~/catkin_ws/src
$ git clone https://github.com/MathRoboticsLab/turtlebot3_sample
$ cd ~/catkin_ws
$ catkin_make

# Run the Code
$ roslaunch turtlebot3_sample sample.launch

Then you can see the laser information printing at the terminal.

# About turtlebot3
More information about the robot can be found at the official website: https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/
