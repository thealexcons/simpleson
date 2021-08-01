cmake_minimum_required (VERSION 3.8)

project(simpleson VERSION 2.0.0)

add_library(${PROJECT_NAME}
    json.cpp
)

target_include_directories(${PROJECT_NAME} PUBLIC .)
add_compile_options(-Wall -Wextra -Werror)
