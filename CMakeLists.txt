cmake_minimum_required(VERSION 3.0.0)
project(algorithm VERSION 0.1.0)

include(CTest)
enable_testing()

SET(EXECUTABLE_OUTPUT_PATH "${PROJECT_SOURCE_DIR}/bin")

add_executable(algorithm ./src/main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
