cmake_minimum_required(VERSION 2.8.3)
project(rosgo_messages)

find_package(catkin REQUIRED COMPONENTS gengo)

catkin_package()

rosgo_generate_messages(
  actionlib_msgs
  ar_track_alvar_msgs
  common_msgs
  concert_msgs
  concert_service_msgs
  diagnostic_msgs
  gateway_msgs
  geometry_msgs
  map_store
  move_base_msgs
  nav_msgs
  rocon_app_manager_msgs
  rocon_device_msgs
  rocon_interaction_msgs
  rocon_service_pair_msgs
  rocon_std_msgs
  rocon_tutorial_msgs
  rosgraph_msgs
  scheduler_msgs
  sensor_msgs
  shape_msgs
  std_msgs
  std_srvs
  stereo_msgs
  tf2_msgs
  trajectory_msgs
  uuid_msgs
  visualization_msgs
  world_canvas_msgs
  yocs_msgs
)

