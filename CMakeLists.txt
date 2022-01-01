cmake_minimum_required(VERSION 3.5)
project(pngsample)
add_executable(pngsample main.cpp)

set(CMAKE_CXX_COMPILER clang++)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++2a")
add_definitions(-Wall -Wextra -O2)