#[[
   @file CMakeLists.txt

   @brief


   // clang-format off
   // clang-format on
]]
cmake_minimum_required(VERSION 3.10)

#Include directories
include_directories()

#Add the sub directories
add_subdirectory(../modules/build modules)

if (DEFINED CONFIG_COMPILE_POSAL)
add_subdirectory(../posal/build posal)
endif()
