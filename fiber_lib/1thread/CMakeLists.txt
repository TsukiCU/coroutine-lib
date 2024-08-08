file(GLOB SRC_LIST "*.cpp")

add_executable(1thread_test ${SRC_LIST})

target_include_directories(1thread_test PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})