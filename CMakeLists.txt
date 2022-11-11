cmake_minimum_required(VERSION 3.15)    # установка версии cmake
project(lab7_cmake)

set(CMAKE_CXX_STANDARD 17)              # установка стандарта языка
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

add_executable(lab7_cmake main.cpp)    # добавление проекта к cmake-файлу