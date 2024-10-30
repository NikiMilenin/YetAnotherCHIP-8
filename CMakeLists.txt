cmake_minimum_required(VERSION 3.11)

include_directories("${PROJECT_SOURCE_DIR}/include")

file(GLOB SRCS "${PROJECT_SOURCE_DIR}/src/*.cpp")

add_executable(CHIP8 ${SRCS})