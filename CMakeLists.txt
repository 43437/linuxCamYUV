cmake_minimum_required(VERSION 2.6)
project(captureoneframe)

add_executable(captureoneframe main.cpp)

install(TARGETS captureoneframe RUNTIME DESTINATION bin)
