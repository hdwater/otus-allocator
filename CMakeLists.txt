cmake_minimum_required(VERSION 3.15)
project(hw4)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(allocator src/allocator.h src/main.cpp)