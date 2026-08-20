cmake_minimum_required(VERSION 3.20)

project(DirScope
    VERSION 0.1.0
    DESCRIPTION "A lightweight C++ command-line tool for analyzing disk usage and finding large files."
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(DirScope
    src/main.cpp
)
