cmake_minimum_required(VERSION 3.30)
project(Lab10)

set(CMAKE_CXX_STANDARD 20)

add_executable(Lab10 exp.cpp parser.cpp scanner.cpp token.cpp visitor.cpp main.cpp)
