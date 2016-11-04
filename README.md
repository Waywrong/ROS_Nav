# README #

```
#!txt

====move_base==================================================
roslaunch mrpt_tutorials r1_gazebo_gh25.launch

roslaunch ros_test1 amcl_demo.launch

roslaunch ros_test1 view_navigation.launch

roslaunch ros_test1 keyboard.launch 
rosrun ros_test1 simple_navigation_goals 

===gmapping===================================================
roslaunch mrpt_tutorials r1_gazebo_gh25.launch 

rosrun gmapping slam_gmapping scan:=/r1/front_laser/scan _odom_frame:=/r1/odom _base_frame:=/r1/base_link _delta:=0.1 _maxUrange:=4.99 _xmin:=-5.0 _ymin:=-5.0 _xmax:=5.0 _ymax:=5.0 _particles:=30 _srr:=0 _srt:=0 _str:=0 _stt:=0.1 _minimumScore:=10000

roslaunch mrpt_tutorials r1_teleop.launch

rosrun map_server map_saver -f mymap

http://blog.csdn.net/chenxingwangzi/article/details/49802763

<<<real robot>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
roslaunch simple_ros_control_main diff_ros_control.launch

rosrun simple_ros_control_main simple_ros_control_main

rosrun hokuyo_node hokuyo_node 

rosrun tf static_transform_publisher 0 0 0 0 0 0 /odom /base_link 100
rosrun tf static_transform_publisher 0 0 0 0 0 0 /base_link /laser 100

rosrun gmapping slam_gmapping scan:=/scan _odom_frame:=/odom _base_frame:=/base_link _delta:=0.1 _maxUrange:=4.99 _xmin:=-5.0 _ymin:=-5.0 _xmax:=5.0 _ymax:=5.0 _particles:=30 _srr:=0 _srt:=0 _str:=0 _stt:=0.1 _minimumScore:=10000

roslaunch ros_test1 keyboard.launch
--
rostopic list
rqt_graph 
rosrun rqt_tf_tree rqt_tf_tree
rosrun rqt_topic rqt_topic
====amcl==================================================
roslaunch mrpt_tutorials r1_gazebo_gh25.launch

roslaunch ros_test1 amcl_r1.launch 

roslaunch mrpt_tutorials r1_teleop.launch

http://blog.csdn.net/chenxingwangzi/article/details/50038413
http://blog.csdn.net/chenxingwangzi/article/details/50388836
https://github.com/chenxingzhe/laser_map
```
