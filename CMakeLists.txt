cmake_minimum_required(VERSION 3.2)
project(IEP_Project VERSION 1.0.0)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
add_executable(IEP_Project 
                app/src/main.cpp
                app/src/Car.cpp
                app/src/Car.h
                )