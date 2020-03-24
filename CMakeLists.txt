cmake_minimum_required(VERSION 3.10)

project(IM_server)

include_directories(./include)

add_executable(${PROJECT_NAME} ./src/server.cpp)