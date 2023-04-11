cmake_minimum_required(VERSION 3.5)

set(CMAKE_CXX_COMPILER  "C:\\msys64\\mingw64\\bin\\g++")
project(HelloApp
    VERSION 0.0.1
    DESCRIPTION "Hello World App"
    LANGUAGES CXX
) 
add_executable(HelloAppBinary main.cpp)
target_compile_features(HelloAppBinary PRIVATE cxx_std_20)