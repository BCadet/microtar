cmake_minimum_required(VERSION 3.10)
add_library(microtar src/microtar.c)
target_include_directories(microtar PUBLIC src)