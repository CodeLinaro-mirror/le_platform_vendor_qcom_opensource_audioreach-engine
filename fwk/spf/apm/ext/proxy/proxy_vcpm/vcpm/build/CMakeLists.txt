#[[
   @file CMakeLists.txt

   @brief


]]
cmake_minimum_required(VERSION 3.10)

#add source and header files
set (lib_srcs_list
    ${LIB_ROOT}/stub_src/vcpm_stub.c
    )

set (lib_incs_list
     ${LIB_ROOT}/inc
    )

#Call spf_build_static_library to generate the static library
spf_build_static_library(vcpm
                         "${lib_incs_list}"
                         "${lib_srcs_list}"
                         "${lib_defs_list}"
                         "${lib_flgs_list}"
                         "${lib_link_libs_list}"
                        )