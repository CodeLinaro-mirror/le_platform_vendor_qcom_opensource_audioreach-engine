#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Include direectories
include_directories(
                    ../core/src
                   )

#Add the sub directories
add_subdirectory(../core/build core)
add_subdirectory(../ext/build ext)
