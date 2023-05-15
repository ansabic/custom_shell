cmake_minimum_required(VERSION 3.25)
project(lsh_master C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(src)

add_executable(lsh_master
        src/main.c)
