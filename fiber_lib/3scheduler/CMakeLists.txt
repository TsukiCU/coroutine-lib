file(GLOB SRC_LIST "*.cpp")

add_executable(3scheduler_test ${SRC_LIST})

target_include_directories(3scheduler_test PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})