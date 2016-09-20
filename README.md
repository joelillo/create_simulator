# Create_simulator
Fork from the osrf irobot create gazebo model.

Implemented changes found here: http://sauravag.com/2015/02/how-to-use-irobot-create-with-ros-indigo/


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
roslaunch create_simulator create_simulator.launch
```
