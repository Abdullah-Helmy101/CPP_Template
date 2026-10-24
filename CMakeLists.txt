cmake_minimum_required(VERSION 3.20)

project(change_Me LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(change_Me
    src/main.cpp
)

target_include_directories(change_Me PRIVATE
    ${CMAKE_INCLUDE_CURRENT_DIR}/include
)