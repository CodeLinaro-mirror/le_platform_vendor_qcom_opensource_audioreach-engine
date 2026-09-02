#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Add the sub directories
add_subdirectory(../capi_cmn/build capi_cmn)
add_subdirectory(../capi_libraries/build capi_libraries)
add_subdirectory(../shared_lib_api/build shared_lib_api)
