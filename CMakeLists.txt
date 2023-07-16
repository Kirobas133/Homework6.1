cmake_minimum_required(VERSION 3.20)
Project(Homework6.1ST)
#add_executable(Homework6.1ST Homework6.1ST.cpp)

add_subdirectory(../Catch2clone/Catch2 Catch2-build)
add_executable(Homework6.1ST Homework6.1ST.cpp)
target_link_libraries(Homework6.1ST PRIVATE Catch2::Catch2)