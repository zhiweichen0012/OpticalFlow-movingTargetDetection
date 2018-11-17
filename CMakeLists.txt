cmake_minimum_required(VERSION 3.12)
project(opticalFlow)

set(CMAKE_CXX_STANDARD 14)

add_executable(opticalFlow main.cpp)
find_package(OpenCV REQUIRED)
target_link_libraries(opticalFlow ${OpenCV_LIBS})