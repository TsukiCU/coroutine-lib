file(GLOB SRC_LIST "*.cpp")

add_executable(5iomanager_test ${SRC_LIST})

target_include_directories(5iomanager_test PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})