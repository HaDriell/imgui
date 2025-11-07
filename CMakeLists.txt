cmake_minimum_required(VERSION 3.10)

project(
    ImGui
    VERSION 1.0
    LANGUAGES CXX
)

add_library(ImGui INTERFACE)
target_include_directories(ImGui
INTERFACE
    ${ImGui_SOURCE_DIR}
)