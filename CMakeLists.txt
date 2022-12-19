cmake_minimum_required(VERSION 3.13)

set(PROJECT_NAME cmake_project_example) # 변수 세팅
set(CMAKE_CXX_SATNDARD 17) #CXX = C++

project(${PROJECT_NAME})
add_executable(${PROJECT_NAME} src/main.cpp) #실행파일 만들기 
