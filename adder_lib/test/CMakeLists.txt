cmake_minimum_required(VERSION 3.13) 
project(test_adder)
add_executable(${PROJECT_NAME} main.cpp)
target_link_directories(${PROJECT_NAME} PRIVATE /usr/local/lib/)
target_link_libraries(${PROJECT_NAME} adder)
