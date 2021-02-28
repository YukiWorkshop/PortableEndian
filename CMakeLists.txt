cmake_minimum_required(VERSION 3.2)
project(PortableEndian)

set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 11)

add_library(PortableEndian INTERFACE)
target_include_directories(PortableEndian INTERFACE .)
