cmake_minimum_required (VERSION 3.4)
project(TSDemux)

set (CMAKE_CXX_STANDARD 17)

option(ENABLE_SAMPLES "Enable samples or not" ON)

add_subdirectory(library)

if (ENABLE_SAMPLES)
add_subdirectory(samples)
endif ()