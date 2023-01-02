cmake_minimum_required(VERSION 3.24)
project(SimpleWindow C)

set(CMAKE_C_STANDARD 11)

Link_Libraries(SDL2)

add_executable(SimpleWindow main.c)
