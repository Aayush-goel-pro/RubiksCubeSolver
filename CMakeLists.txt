cmake_minimum_required(VERSION 3.24)
project(RubiksCubeSolver)

set(CMAKE_CXX_STANDARD 14)

add_executable(RubiksCubeSolver main.cpp GenericRubiksCube.cpp GenericRubiksCube.h)
