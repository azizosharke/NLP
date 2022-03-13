cmake_minimum_required(VERSION 3.20)
project(Assignment1)

set(CMAKE_CXX_STANDARD 14)

add_executable(Assignment1 cmake-build-debug/Node.cpp cmake-build-debug/Node.h cmake-build-debug/tester.cpp cmake-build-debug/FSA.cpp cmake-build-debug/FSA.h)
