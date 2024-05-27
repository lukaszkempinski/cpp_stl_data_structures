cmake_minimum_required(VERSION 3.22)

if (NOT DEFINED CMAKE_CXX_STANDARD)
    set(CMAKE_CXX_STANDARD 20)
endif()

set(CMAKE_CXX_EXTENSIONS        OFF)

project(
  myproject
  VERSION 0.0.1
  DESCRIPTION ""
  LANGUAGES CXX C)

set(LIBRARY_NAME Library)
set(EXECUTABLE_NAME Executable)

add_subdirectory(configure)
add_subdirectory(src)
add_subdirectory(app)