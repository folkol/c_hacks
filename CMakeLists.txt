cmake_minimum_required(VERSION 3.5)
project(c_hacks)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c11")

set(SOURCE_FILES wc.c)
add_executable(c_hacks ${SOURCE_FILES})