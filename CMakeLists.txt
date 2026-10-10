cmake_minimum_required(VERSION 3.10)
project(riscv_simulator LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXE_LINKER_FLAGS "-static -s")



add_executable(code main.cpp)
