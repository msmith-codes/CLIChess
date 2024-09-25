cmake_minimum_required(VERSION 3.25)
project(CLIChess)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCES 
    src/main.cpp
)

add_executable(CLIChess ${SOURCES})

target_include_directories(CLIChess PRIVATE ${CMAKE_SOURCE_DIR}/include)


