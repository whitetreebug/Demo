cmake_minimum_required(VERSION 3.10)

project(Demo)

set(CMAKE_CXX_STANDARD 17)
# set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17 -O3")

add_executable(${PROJECT_NAME}  main.cpp)


INSTALL(TARGETS ${PROJECT_NAME}
       RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)