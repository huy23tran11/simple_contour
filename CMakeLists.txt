project(OBSTACLE_REG)
cmake_minimum_required(VERSION 2.6 FATAL_ERROR)

find_package(OpenCV REQUIRED)

# Project Executable
add_executable (region_separation region_separation.cpp )
target_link_libraries(region_separation ${OpenCV_LIBS})
