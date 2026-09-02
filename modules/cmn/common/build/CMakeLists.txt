#[[
   @file CMakeLists.txt

   @brief

]]
cmake_minimum_required(VERSION 3.10)

#Include directories
include_directories(
                    ../internal_api/imcl/api
                   )

#Add the sub directories
add_subdirectory(../utils/build utils)
