cmake_minimum_required(VERSION 3.20)
project(Assignment3)

set(CMAKE_CXX_STANDARD 14)

add_executable(Assignment3 cmake-build-debug/TDPARSE_hw_start.cpp cmake-build-debug/td_tester.cpp cmake-build-debug/PDA.cpp cmake-build-debug/PDA.h cmake-build-debug/TDPARSE.h cmake-build-debug/rules.h)
