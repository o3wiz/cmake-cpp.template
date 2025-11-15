cmake_minimum_required(VERSION 4.1.1)

project(Temp LANGUAGES CXX)

add_executable(main "Main.cpp")
target_compile_features(main PRIVATE cxx_std_23)
