
ROS is a very useful tool in robotics, providing and essential system to study and improve robotics applications.
This document covers the steps we applied to establish the basic programs and tools to be able to operate modules on ROS.
In our case, we are working on a robotic arm.

Installing Ubuntu on dual boot with Windows.
	First things first, ROS environment is implemented on Ubuntu, If you don't have it already, you can follow this guide:
  https://www.lifewire.com/ultimate-windows-7-ubuntu-linux-dual-boot-guide-2200653 
  
Installing ROS and preparing its environment.
	Go to http://wiki.ros.org/ROS/Tutorials and follow through the tutorial steps. Get used to the context and the coding language.
  If you are using Ubuntu for the first time(probably you are) go check out http://www.ee.surrey.ac.uk/Teaching/Unix/ 
	Once you are familiar with the environment, done with the tutorials, and have your catkin workspace ready, you can move on to 
  working with your project.

  Download the necessary packages to your workspace e.g: catkinws/src >>
  update the workspace 
  $ wstool update -t src 
>>
  running the program >>
  $ roslaunch phantomx_pincher_robot_arm_edited_moveit_config moveit_gui_all.launch >>
  $ roslaunch phantomx_pincher_robot_arm_edited_moveit_config arm.launch
