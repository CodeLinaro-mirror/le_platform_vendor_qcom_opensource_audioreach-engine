#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#Include directories
include_directories(
                    ${LIB_ROOT}/inc
                    ../cmn/inc
                    ../core/src
                    ../ext/cntr_proc_dur_fwk_ext/inc
                    ../ext/cntr_frame_dur_fwk_ext/inc
                    ../ext/sync_fwk_ext/inc
                    ../ext/voice_delivery_fwk_ext/inc
                   )

#Add the sub directory
add_subdirectory(../core/build core)
if (CONFIG_SPL_CNTR_EXT)
add_subdirectory(../ext/build ext)
endif()