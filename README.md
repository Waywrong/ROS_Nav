# README #

```
#!txt
====gmapping&move_base==================================================
<gazebo>
roslaunch mrpt_tutorials r1_gazebo_gh25.launch 
roslaunch ros_test1 gmapping_demo.launch
roslaunch ros_test1 view_navigation.launch
roslaunch mrpt_tutorials r1_teleop.launch 

<real robot>
roslaunch simple_ros_control_main diff_ros_control.launch 
rosrun simple_ros_control_main simple_ros_control_main 
roslaunch ros_test1 real_gmapping.launch
roslaunch ros_test1 view_navigation.launch 
roslaunch ros_test1 keyboard.launch 
====amcl&move_base==================================================
<gazebo>
roslaunch mrpt_tutorials r1_gazebo_gh25.launch 
roslaunch ros_test1 amcl_demo.launch
roslaunch ros_test1 view_navigation.launch
roslaunch mrpt_tutorials r1_teleop.launch
rosrun ros_test1 simple_navigation_goals 

<real robot>
roslaunch simple_ros_control_main diff_ros_control.launch 
rosrun simple_ros_control_main simple_ros_control_main 
roslaunch ros_test1 real_amcl.launch
roslaunch ros_test1 view_navigation.launch 
roslaunch ros_test1 keyboard.launch 


http://blog.csdn.net/chenxingwangzi/article/details/50038413
http://blog.csdn.net/chenxingwangzi/article/details/50388836
https://github.com/chenxingzhe/laser_map
```
