cmake_minimum_required(VERSION 3.5.1)

project(math)

include_directories(../inc)

add_library(mathCalc STATIC ../src/mathCalc.cpp)

install(TARGETS mathCalc DESTINATION lib)
install(FILES ../inc/mathCalc.h DESTINATION include)