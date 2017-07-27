cmake_minimum_required(VERSION 3.7)
project(Progra3Tarea2_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bin/Debug/Tarea1
        bin/Debug/Tarea2
        Evaluador.cpp
        Evaluador.h
        LICENSE
        main.cpp
        README.md
        Tarea2.cbp
        Tarea2.depend
        Tarea2.layout)

add_executable(Progra3Tarea2_master ${SOURCE_FILES})