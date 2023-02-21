cmake_minimum_required(VERSION 3.13) 
project(cmake_test)
add_executable(${PROJECT_NAME} main.cpp)
install(TARGETS ${PROJECT_NAME} DESTINATION bin)
