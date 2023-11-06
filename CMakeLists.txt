cmake_minimum_required(VERSION 3.26)
project(cpp_not_so_simple_calculator)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(cpp_not_so_simple_calculator
        main.cpp
        Tester.hpp)
