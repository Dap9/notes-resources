cmake_minimum_required(VERSION 3.29 FATAL_ERROR)
project(lib_linking LANGUAGES C)

add_library(hello_world_lib
  STATIC
  lib.c
)

add_executable(hello_world
  main.c
)

target_link_libraries(hello_world
  hello_world_lib
)
