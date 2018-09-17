# Minimum CMake Required
cmake_minimum_required(VERSION 3.11)
# interface library for project
add_library(test INTERFACE) 
add_subdirectory(src)
add_subdirectory(test)

