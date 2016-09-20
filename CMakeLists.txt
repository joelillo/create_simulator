project(create_simulator)

# Get the information about this package's buildtime dependencies
  find_package(catkin REQUIRED
    COMPONENTS)


  # Declare that this catkin package's runtime dependencies
  catkin_package(
   CATKIN_DEPENDS gazebo7
  )
