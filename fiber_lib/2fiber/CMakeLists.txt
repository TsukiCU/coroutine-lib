file(GLOB SRC_LIST "*.cpp")

add_executable(2fiber_test ${SRC_LIST})

target_include_directories(2fiber_test PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})