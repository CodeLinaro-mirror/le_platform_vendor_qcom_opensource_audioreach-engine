#[[
   @file CMakeLists.txt

   @brief


]]

#Include directories
include_directories(
                    ../alsa_device/api
                   )

add_subdirectory(../alsa_device/build alsa_device)
