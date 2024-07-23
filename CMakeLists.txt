cmake_minimum_required(VERSION 3.26)
project(HBUILDS LANGUAGES CXX)

file(GLOB HBUILDS_SOURCE source/*)
add_executable(hbuild ${HBUILDS_SOURCE})
target_include_directories(hbuild PRIVATE include)