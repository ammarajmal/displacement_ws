cmake_minimum_required(VERSION 3.0.2)
project(camera_driver_gige)
find_package(catkin REQUIRED COMPONENTS
  cv_bridge
  rospy
  sensor_msgs
  camera_info_manager_py
)
#catkin_python_setup()
catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES camera_driver_gige
#  CATKIN_DEPENDS rospy sensor_msgs
#  DEPENDS system_lib
)
include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
#catkin_install_python(PROGRAMS
#  scripts/cam_node.py
#  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
#)
