cmake_minimum_required(VERSION 3.0)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c11")

project(Hello)

add_executable(
   hello
   main_hello.c
)

add_executable(
   hallo
   main_hallo.c
)

add_executable(
   age
   main_age.c
)
