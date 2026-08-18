cmake_minimum_required(VERSION 3.12)

project(HW2)

add_executable(HW2 
    example_function.h
    example_function.cpp
    move_me_out.h
    move_me_out.cpp
    hello_world.cpp
    )

set_target_properties(HW2 PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)