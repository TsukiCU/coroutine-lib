cmake_minimum_required(VERSION 3.10)
project(CPP_COROUTINE)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(1thread)
add_subdirectory(2fiber)
add_subdirectory(3scheduler)
add_subdirectory(4timer)
add_subdirectory(5iomanager)
add_subdirectory(6hook)