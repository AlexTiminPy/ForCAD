cmake_minimum_required (VERSION 3.8)

add_executable (application "main.cpp")
include_directories(${CMAKE_SOURCE_DIR}/library)

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET application PROPERTY CXX_STANDARD 20)
endif()

