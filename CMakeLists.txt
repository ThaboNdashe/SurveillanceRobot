cmake_minimum_required(VERSION 3.22)
project(Surveillance_Robot)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Surveillance_Robot
        camera_pins.h
        camera_wrap.cpp
        camera_wrap.h
        SurveillanceRobot.ino)
