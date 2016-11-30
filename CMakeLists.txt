cmake_minimum_required(VERSION 2.8.3)
project(lower_step_detector)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  roslaunch
  sensor_msgs
  std_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

roslaunch_add_file_check(test/lower_step_detector_launch.test.xml)
roslaunch_add_file_check(test/lower_step_detector_demo_launch.test.xml)
