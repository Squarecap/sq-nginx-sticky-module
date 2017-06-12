cmake_minimum_required(VERSION 3.6)
project(nginx_sticky_modified)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES library.c library.h)
add_library(nginx_sticky_modified ${SOURCE_FILES})