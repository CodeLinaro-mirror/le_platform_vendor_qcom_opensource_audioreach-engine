#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Add the sub directories
add_subdirectory(../container_utils/build container_utils)
add_subdirectory(../graph_utils/build graph_utils)
add_subdirectory(../icb/build icb)
add_subdirectory(../topologies/build topologies)
