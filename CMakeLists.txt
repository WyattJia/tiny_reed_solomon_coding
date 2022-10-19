cmake_minimum_required(VERSION 3.23)
project(tiny_reed_solomon_coding)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(tiny_reed_solomon_coding
        src/matrix.cpp
        src/reed_solomon.cpp
        src/reed_solomon.h
        src/sample_decoder.cpp
        src/sample_encoder.cpp)
