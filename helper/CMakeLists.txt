cmake_minimum_required(VERSION 2.8)

# Includes
include_directories(
    "../externals/glslang"
    "../externals/SPIRV-Tools/external/include"
)

# Library
add_library(glslangjs_helper
    "glslangjs_helper.cpp"
)
