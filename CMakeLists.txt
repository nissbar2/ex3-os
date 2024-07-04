cmake_minimum_required(VERSION 3.22)
project(ex3-os)

set(CMAKE_CXX_STANDARD 14)

include_directories(Resources)

add_executable(ex3-os
        Atomic/atomicdemo.cpp
#        Atomic/atomicdemo_multivar.cpp
#        Barrier/Barrier.cpp
#        Barrier/Barrier.h
#        Barrier/barrierdemo.cpp

        )