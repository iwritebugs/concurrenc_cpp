cmake_minimum_required(VERSION 3.16)
project(concurrenc_cpp)

set(CMAKE_CXX_STANDARD 20)

add_executable(concurrenc_cpp main.cpp)

target_link_libraries(concurrenc_cpp pthread)