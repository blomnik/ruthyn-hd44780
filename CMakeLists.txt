cmake_minimum_required(VERSION 3.24)
project(ruthyn_hd44780 C)

set(CMAKE_C_STANDARD 11)

add_compile_options(-O3 -fpic -shared)
add_library(ruthyn_hd44780 SHARED ruthyn-hd44780.c)
