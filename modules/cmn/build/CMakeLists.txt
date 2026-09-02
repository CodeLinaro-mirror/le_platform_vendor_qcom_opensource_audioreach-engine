#[[
   @file CMakeLists.txt

   @brief

]]
cmake_minimum_required(VERSION 3.10)

#Include directories
include_directories(
                    ${LIB_ROOT}/api
                   )

#Add the sub directories
add_subdirectory(${LIB_ROOT}/common/build common)
