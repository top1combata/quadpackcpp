cmake_minimum_required(VERSION 3.10)


project(quadpackcpp LANGUAGES CXX)

add_subdirectory(src)

if (BUILD_EXAMPLES)
    add_subdirectory(examples)
endif()