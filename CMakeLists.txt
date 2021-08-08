cmake_minimum_required(VERSION 3.19)
project(Algo)

set(CMAKE_CXX_STANDARD 20)

add_executable(Algo main.cpp Graph.cpp Graph.h AdjacentList.cpp AdjacentList.h Queue.cpp Queue.h IO.cpp IO.h)