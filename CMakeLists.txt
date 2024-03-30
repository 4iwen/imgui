cmake_minimum_required(VERSION 3.27)
project(ImGui)

add_library(
        ImGui STATIC

        imgui.cpp
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_widgets.cpp
        imgui_tables.cpp
)