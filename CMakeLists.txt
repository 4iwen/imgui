cmake_minimum_required(VERSION 3.6)
project(ImGui LANGUAGES CXX)

add_library(
        ImGui STATIC

        imgui.cpp
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_widgets.cpp
        imgui_tables.cpp
)