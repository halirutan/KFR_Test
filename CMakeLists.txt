cmake_minimum_required(VERSION 3.17)
project(KFR_Test)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(kfr)
add_executable(KFR_Test main.cpp)
target_link_libraries(KFR_Test kfr kfr-dft)