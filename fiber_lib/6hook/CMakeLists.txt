file(GLOB SRC_LIST "*.cpp")

add_executable(6hook_test ${SRC_LIST})

target_include_directories(6hook_test PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})