# CMakeList.txt : CMake project for SPP, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("spp")

# Add source to this project's executable.
add_executable (spp  "src/main.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET spp PROPERTY CXX_STANDARD 20)
endif()

# TODO
