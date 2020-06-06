cmake_minimum_required(VERSION 3.2)
project(imgui)

add_library(${PROJECT_NAME} STATIC imgui.cpp imgui_widgets.cpp imgui_draw.cpp)

target_include_directories(${PROJECT_NAME} PUBLIC ${PROJECT_SOURCE_DIR})
