cmake_minimum_required(VERSION 3.2)
project(portable-endian)

set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_library(portable-endian portable-endian.h)
set_target_properties(portable-endian PROPERTIES LINKER_LANGUAGE CXX)