cmake_minimum_required(VERSION 3.15)
project(Hello_World_on_CPP LANGUAGES CXX)

# Включаем 17-й стандарт C++
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Указываем, что хотим собрать программу CalculatorApp из файла Calculator.cpp
add_executable(CalculatorApp main.cpp)