cmake_minimum_required(VERSION 3.17 FATAL_ERROR)

project(Network-Monitor)

set(SOURCES "${CMAKE_CURRENT_SOURCE_DIR}/src/main.cpp")

add_executable(Network-Monitor ${SOURCES})
target_compile_features(Network-Monitor
    PRIVATE
        cxx_std_11
)