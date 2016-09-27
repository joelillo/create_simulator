# Create_simulator
This project wraps the OSRF iRobot Create Gazebo model with ROS plugins to expose the simulation controls to the ROS environment.

Implemented changes found here:
 http://sauravag.com/2015/02/how-to-use-irobot-create-with-ros-indigo/

# Version

The current simulator version supports ROS Kinetic on Ubuntu 16.04.

# Setup
Install ROS:

http://wiki.ros.org/ROS/Installation

Setup a catkin workspace:

http://wiki.ros.org/catkin/Tutorials

Clone this package into your catkin workspace.

# Install
```
cd ~/[path_to_your_catkin_workspace]
```

```
rosdep update
```

```
rosdep install --from-paths src --ignore-src --rosdistro kinetic
```

# Run
```
source devel/setup.bash
```

```
roslaunch create_simulator create_simulator.launch
```
