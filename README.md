# AGV evaluation description

This ROS package contains URDF file to use AGV evaluation with ROS 1.
The URDF contains also contains the collision model and is suitable for Gazebo simulations. 
The package has been tested with Melodic.

## Quickstart

Launch the following command in order to run AGV sample1:
```
$ mkdir -p catkin_ws/src
$ git clone https://github.com/Panasonic-Advanced-Technology/agv_eval_description.git
$ cd ..
$ source /opt/ros/melodic/setup.bash
$ catkin build
$ source devel/setup.bash
$ roslaunch agv_eval_description gazebo.launch sample:=sample1
```

Launch the following command in order to run AGV sample2:
```
$ roslaunch agv_eval_description gazebo.launch sample:=sample2
```
