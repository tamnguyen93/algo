cmake_minimum_required(VERSION 3.11.0)
project(algo)

include_directories(${CMAKE_SOURCE_DIR}/include)

add_executable(${PROJECT_NAME}
                   src/algo.cpp)
