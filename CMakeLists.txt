cmake_minimum_required(VERSION 3.0.2)
project(lmf_launch)


find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
)

catkin_package(
  CATKIN_DEPENDS roscpp rospy
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)