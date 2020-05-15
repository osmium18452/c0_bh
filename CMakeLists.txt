cmake_minimum_required(VERSION 3.16)
project(c0_bh)

set(CMAKE_CXX_STANDARD 14)

add_executable(c0_bh main.cpp headers/common.h headers/error.h src/error.cpp headers/grammar.h src/grammar.cpp src/midcode.cpp headers/midcode.h src/mips.cpp headers/mips.h headers/symbol.h src/symbol.cpp headers/table.h src/table.cpp)