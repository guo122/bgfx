cmake_minimum_required (VERSION 3.0.2)

project(bgfx)

set(CMAKE_ROOT_DIR "${CMAKE_CURRENT_LIST_DIR}")

include(${CMAKE_ROOT_DIR}/BuildScript/cmake/Build.cmake)

# enable project folders
set_property(GLOBAL PROPERTY USE_FOLDERS ON)
set_property(GLOBAL PROPERTY PREDEFINED_TARGETS_FOLDER "CMake")

add_subdirectory(src)
