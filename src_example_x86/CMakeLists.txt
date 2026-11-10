cmake_minimum_required(VERSION 3.10)

project(HelloWorldX86 CXX)

# Define el archivo ejecutable
add_executable(hello_world_x86 main_example_x86.cpp)

# Enlazado estatico de las librerias
target_link_options(hello_world_x86 PRIVATE
    -static
)
