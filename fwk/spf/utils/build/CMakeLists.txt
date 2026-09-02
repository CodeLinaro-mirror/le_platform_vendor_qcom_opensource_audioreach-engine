#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Add the sub directories
add_subdirectory(../cmn/build cmn)
add_subdirectory(../interleaver/build interleaver)
add_subdirectory(../list/build list)
add_subdirectory(../lpi_pool/build lpi_pool)
add_subdirectory(../watchdog_svc/build watchdog_svc)
