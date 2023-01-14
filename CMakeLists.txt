cmake_minimum_required (VERSION 3.8)

project ("ForCAD")

add_subdirectory (library)
add_subdirectory (application)

add_dependencies(application triangle_area_lib)
