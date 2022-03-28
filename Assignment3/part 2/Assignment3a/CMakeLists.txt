cmake_minimum_required(VERSION 3.20)
project(Assignment3a)

set(CMAKE_CXX_STANDARD 14)

add_executable(Assignment3a TDPARSE_BT_hw_start.cpp td_bt_tester.cpp BT_ITEM.h PDA.h rules.h TDPARSE_BT.h TDPARSE.h)

