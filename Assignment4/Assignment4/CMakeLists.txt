cmake_minimum_required(VERSION 3.20)
project(Assignment4)

set(CMAKE_CXX_STANDARD 14)

add_executable(Assignment4  CHART_hw_start.cpp rules.cpp  CHART.H rules.h chart_tester.cpp)

## add_executable(Assignment3a TDPARSE_BT_hw_start.cpp rules.cpp td_bt_tester.cpp BT_ITEM.h PDA.h rules.h TDPARSE_BT.h TDPARSE.h)
