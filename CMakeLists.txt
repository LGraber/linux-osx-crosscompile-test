cmake_minimum_required(VERSION 3.1.0)
project(cross-compile-test CXX)

set(CMAKE_CXX_STANDARD 17)

add_executable(cross-compile-test main.cpp)

install(TARGETS cross-compile-test DESTINATION bin)
