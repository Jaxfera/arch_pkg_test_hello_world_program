cmake_minimum_required(VERSION 3.13)
project(hello_world LANGUAGES CXX VERSION 1.0.0)
add_executable(hello_world "${CMAKE_CURRENT_SOURCE_DIR}/src/hello.cpp")

