# What version of CMake is require for this project
cmake_minimum_required(VERSION 3.10)

# Name of the project and languages used (C/C++ are default)
project(Example1 LANGUAGES CXX)

# Adds an example to the project, single source file
add_executable(example1 example1.cxx)
