cmake_minimum_required(VERSION 3.17)
project(c_demo C)

set(CMAKE_C_STANDARD 11)

aux_source_directory(src DIR_SRCS)

add_executable(c_demo main.c)
add_executable(hello test.c ${DIR_SRCS})
