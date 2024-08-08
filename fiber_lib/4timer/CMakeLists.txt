file(GLOB SRC_LIST "*.cpp")

add_executable(4timer_test ${SRC_LIST})

target_include_directories(4timer_test PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})