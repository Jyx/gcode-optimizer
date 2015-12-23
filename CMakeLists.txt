cmake_minimum_required(VERSION 3.0)
project (gcode-optimizer)

set (GCODE_OPTIMIZER_VERSION_MAJOR 1)
set (GCODE_OPTIMIZER_VERSION_MINOR 0)
set (CMAKE_CXX_FLAGS "--std=gnu++11 ${CMAKE_CXX_FLAGS}")

add_executable(gcodemillopt gcodemillopt.cpp)
