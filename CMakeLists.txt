cmake_minimum_required(VERSION 3.22.1)

project("Hello world")

include_directories(lib/inc)
add_subdirectory(lib)
add_subdirectory(src)