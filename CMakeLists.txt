cmake_minimum_required(VERSION 3.27)
project(MSDI_LAB_4)

set(CMAKE_CXX_STANDARD 14)

include_directories(lab_4)

add_executable(MSDI_LAB_4
        lab_4/DES.h
        lab_4/lab_4.cpp
        lab_4/Tables.h)
