cmake_minimum_required(VERSION 3.10)

project(grpcpp-cli-demo)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "-fopenmp")
set(CMAKE_EXE_LINKER_FLAGS -static)

add_executable(grpcpp-cli main.cpp main.cpp)