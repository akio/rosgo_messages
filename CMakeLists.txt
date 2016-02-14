cmake_minimum_required(VERSION 2.8.3)
project(rosgo_messages)

find_package(catkin REQUIRED COMPONENTS
  message_generation
  rosgo_build_tools
  rosgo_core
)

catkin_package()

rosgo_generate_messages(
  std_srvs
  actionlib_msgs
  geometry_msgs
  sensor_msgs
  nav_msgs
)

