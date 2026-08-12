#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Include directories
include_directories(
                    ../cmn/inc
                    ../core/src
                   )

#Add the sub directory
add_subdirectory(../core/build core)
