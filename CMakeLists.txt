cmake_minimum_required(VERSION 3.10...3.29)
project(glad LANGUAGES C VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_library(glad src/gl.c)

target_include_directories(glad PUBLIC include/)
target_include_directories(glad PRIVATE src/)