cmake_minimum_required(VERSION 2.8.0)
project(create_simulator)

# Get the information about this package's buildtime dependencies
  find_package(catkin REQUIRED
    COMPONENTS)


  # Declare that this catkin package's runtime dependencies
  catkin_package(
   CATKIN_DEPENDS gazebo_ros gazebo_plugins teleop_twist_keyboard
  )
