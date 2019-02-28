cmake_minimum_required(VERSION 2.8)
project(qrcodegen)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_library(${PROJECT_NAME} SHARED
        BitBuffer.cpp
        BitBuffer.hpp
        QrCode.cpp
        QrCode.hpp
        QrSegment.cpp
        QrSegment.hpp)
