
cmake_minimum_required (VERSION 3.8)

add_library(triangle_area_lib SHARED "triangle_area.cpp" "triangle_area.h")


if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET triangle_area_lib PROPERTY CXX_STANDARD 20)
endif()

