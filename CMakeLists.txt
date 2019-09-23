# cmake for hunter

cmake_minimum_required(VERSION 2.8.9 FATAL_ERROR)

project(zstd)

set(ZSTD_BUILD_PROGRAMS OFF)

add_subdirectory("build/cmake")
