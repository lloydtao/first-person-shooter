cmake_minimum_required(VERSION 3.16)
project(src)

set(CMAKE_CXX_STANDARD 14)
link_libraries(ws2_32)

add_executable(src main.cpp config.h server.cpp server.h client.cpp client.h)