# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

project ("libxml2-2.9.10")

# Include sub-projects.
add_subdirectory ("vendor/zlib-1.2.11")
add_subdirectory ("vendor/libiconv-1.16")
add_subdirectory ("vendor/liblzma-5.2.4")
add_subdirectory ("vendor/libxml2-2.9.10")
