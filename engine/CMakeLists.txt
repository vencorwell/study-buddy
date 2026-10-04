cmake_minimum_required(VERSION 3.20)

project(StudyBuddyEngine LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(sb src/main.cpp)

target_compile_options(sb PRIVATE -Wall -Wextra)
