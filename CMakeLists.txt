cmake_minimum_required(VERSION 3.10)

project(ImGuizmo)

set(CMAKE_CXX_STANDARD 11)

set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(ImGuizmo STATIC
    ImGuizmo.cpp
    ImGuizmo.h
)

target_include_directories(ImGuizmo PRIVATE "../imgui")

target_include_directories(ImGuizmo PUBLIC .)
