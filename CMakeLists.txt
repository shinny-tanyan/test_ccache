cmake_minimum_required(VERSION 3.13)
project(TEST)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_INSTALL_RPATH_USE_LINK_PATH TRUE)

add_executable(test main.cpp)