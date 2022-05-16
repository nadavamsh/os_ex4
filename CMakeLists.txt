cmake_minimum_required(VERSION 3.20)
project(os_ex4 C CXX)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(os_ex4
        MemoryConstants.h
        PhysicalMemory.cpp
        PhysicalMemory.h
        SimpleTest.cpp
        VirtualMemory.h)

