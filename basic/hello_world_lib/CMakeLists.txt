cmake_minimum_required(VERSION 3.29 FATAL_ERROR)
project(hello_world_lib LANGUAGES C)

add_library(hello_world
  STATIC
  hello_world.c
)
