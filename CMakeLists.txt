cmake_minimum_required(VERSION 2.8.3)
project(lower_step_detector)

find_package(catkin REQUIRED COMPONENTS
  sensor_msgs
  std_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
