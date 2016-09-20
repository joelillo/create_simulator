# create_simulator
Fork from the osrf irobot create gazebo model.


# Usage
**Start ROS and Gazebo**

```
roslaunch gazebo_ros empty_world.launch
```

```
rosrun gazebo_ros  spawn_model -file ~/catkin_workspace/src/create/model-1_4.sdf -sdf -model create
```

```
rostopic pub /cmd_vel geometry_msgs/Twist -- '[1.0, 0.0, 0.0]' '[0.0, 0.0, 1]'
```
