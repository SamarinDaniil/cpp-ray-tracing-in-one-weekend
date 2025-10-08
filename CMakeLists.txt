cmake_minimum_required(VERSION 3.31.6)
project(RayTracingInOneWeekend)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(raytracer src/main.cpp)

target_include_directories(raytracer PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)