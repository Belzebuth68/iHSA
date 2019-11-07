cmake_minimum_required(VERSION 3.12)
project(iHSA)

set(CMAKE_CXX_STANDARD 17)

add_executable(iHSA main.cpp MyAlgorithm.cpp MyAlgorithm.h Problem.cpp Problem.h SetUpParams.cpp SetUpParams.h Solution.cpp Solution.h )