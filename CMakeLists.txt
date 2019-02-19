cmake_minimum_required(VERSION 3.5)

project(Anthill)

set(CMAKE_BINARY_DIR ${PROJECT_SOURCE_DIR}/build)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

add_executable(Anthill
	src/main.c)


