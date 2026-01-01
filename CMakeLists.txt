cmake_minimum_required(VERSION 3.15)
project(clox C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_C_EXTENSIONS OFF)

add_executable(${PROJECT_NAME}
    src/main.c
    src/debug.c
    src/chunk.c
    src/memory.c
)
