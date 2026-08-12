#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Add the sub directories
add_subdirectory(../gen_topo/build gen_topo)
if(CONFIG_SPECIAL_TOPOLOGY)
add_subdirectory(../spl_topo/build spl_topo)
endif()
add_subdirectory(../topo_utils/build topo_utils)
