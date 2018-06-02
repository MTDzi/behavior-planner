project(behavior_planner)

cmake_minimum_required (VERSION 3.5)

add_definitions(-std=c++14)

set(CXX_FLAGS "-Wall")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")

set(sources src/main.cpp src/vehicle.cpp src/cost.cpp src/road.cpp)

add_executable(behavior_planner ${sources})