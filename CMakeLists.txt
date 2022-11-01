cmake_minimum_required(VERSION 3.23.2)
project(untitled5)

set(CMAKE_CXX_STANDARD 14)
find_package(SQLite3 REQUIRED net gl core base)
#include(${SQLite3_LIBRARIES})
add_executable(untitled5 main.cpp)
target_link_libraries(untitled5 ${SQLite3_LIBRARIES})