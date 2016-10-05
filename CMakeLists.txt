cmake_minimum_required(VERSION 2.8.7)
project(Desctop_try)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES draft_unique_ptr.cpp)
add_executable(Desctop_try ${SOURCE_FILES})
