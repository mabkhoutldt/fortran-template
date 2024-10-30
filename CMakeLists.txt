CMAKE_MINIMUM_REQUIRED(VERSION 3.15.2)
PROJECT(myProject)

enable_language(Fortran)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/run)
add_subdirectory(source)
