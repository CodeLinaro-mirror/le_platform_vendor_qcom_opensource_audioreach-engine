#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Add the sub directories
add_subdirectory(../cntr_proc_dur_fwk_ext/build cntr_proc_dur_fwk_ext)
add_subdirectory(../sync_fwk_ext/build sync_fwk_ext)
add_subdirectory(../voice_delivery_fwk_ext/build voice_delivery_fwk_ext)
