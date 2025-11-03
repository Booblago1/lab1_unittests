cmake_minimum_required(VERSION 4.0)
project(lab1_unittests)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab1_unittests
        student_manager.cpp
        student_manager.h
        test.cpp)
